```mermaid
graph TD;
    User -->|Registration Information| User_Registration[1. User Registration and Login]
    User_Registration -->|Login Credentials| User_Data[User Data]
    User -->|Login Credentials| User_Registration
    User_Registration --> Select_Service[2. Select Service (Ride, Food, Courier)]
    
    Select_Service -->|Service Request| Food_Ordering[3. Food Ordering]
    Select_Service -->|Service Request| Ride_Sharing[4. Ride Sharing]
    Select_Service -->|Service Request| Courier_Service[5. Courier Service]
    
    Food_Ordering -->|Request Menu| Restaurant_Data[Restaurant Data]
    Food_Ordering -->|Send Menu| User
    Food_Ordering -->|Place Order| Order_Data[Order Data]
    Food_Ordering -->|Send Order Details| Restaurant_Authority[Restaurant Authority]
    Restaurant_Authority -->|Confirm Order| Food_Ordering
    
    Ride_Sharing -->|Enter Destination| Ride_Data[Rider Data]
    Ride_Sharing -->|Send Ride Details| Rider
    Rider -->|Accept Ride| Ride_Sharing
    Ride_Sharing -->|Assign Rider| User
    
    Courier_Service -->|Enter Parcel Details| Order_Data
    Courier_Service -->|Send Courier Details| Rider
    Rider -->|Accept Courier Job| Courier_Service
    Courier_Service -->|Assign Rider| User
    
    Food_Ordering --> Payment_Processing[6. Payment Processing]
    Ride_Sharing --> Payment_Processing
    Courier_Service --> Payment_Processing
    
    Payment_Processing -->|Payment Information| Order_Data
    Payment_Processing --> Receipt_Generation[7. Receipt Generation]
    Receipt_Generation -->|Receipt| User
    
    subgraph Data_Stores
        Restaurant_Data
        Rider_Data
        Order_Data
        User_Data
    end
    
    subgraph External_Entities
        Restaurant_Authority
        Rider
    end