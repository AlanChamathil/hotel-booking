# Data Preprocessing

## Final Features

The following are the finalised features that will be used for modelling

| No. | Feature | Description | Data Type |
|:---:|----------|-------------|-----------|
| 1 | `is_canceled` | Target variable indicating whether a booking was cancelled. | Binary |
| 2 | `lead_time` | Number of days between booking date and arrival date. | Numerical |
| 3 | `arrival_date_week_number` | Week number of the scheduled arrival. | Numerical |
| 4 | `arrival_date_day_of_month` | Day of the month the guest was scheduled to arrive. | Numerical |
| 5 | `total_stay` | Total number of nights stayed (weekend + weekday nights). | Numerical |
| 6 | `total_attendance` | Total number of guests (adults + children + babies). | Numerical |
| 7 | `meal` | Meal plan selected for the booking. | Categorical |
| 8 | `country` | Guest's country of origin. | Categorical |
| 9 | `market_segment` | Booking market segment (e.g., Online TA, Direct, Groups). | Categorical |
| 10 | `reserved_room_type` | Room type originally reserved by the guest. | Categorical |
| 11 | `assigned_room_type` | Room type assigned upon arrival. | Categorical |
| 12 | `deposit_type` | Deposit policy associated with the booking. | Categorical |
| 13 | `adr` | Average Daily Rate (average revenue per occupied room per night). | Numerical |
| 14 | `total_of_special_requests` | Number of special requests made by the guest. | Numerical |


