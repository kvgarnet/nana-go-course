### source link 
https://www.youtube.com/watch?v=yyUHQIec83I

## Notes

#### variable declaration

```
var aInt int
aString := "string"
var aBool = false
```

#### Package level variables

Can only be declared or defind with var syntax

```
var conferenceRoom = "Golang conference"
var remainingTickets uint = 50
var bookings = []string{}
const conferenceTicket uint = 50
```
#### Switch statemt
```
city := "Hyderabad"

switch city {
    case "London","Berlin":
    //some way of executing
    case "Hyderabad", "London":
    //Indian
    case "Sinagapore":
    //Singapore business
    default:
    //Default way of handling
}
```

#### maps

```
//creating empty map
var userData = make(map[string]string)
//adding a key-value pair
userData["u00001"] = "John Doe john.doe@outlook.com 25"
userData["u00002"] = strconv.FormatUint(uint64(7), 10) //convertig uint to string

//slice of maps
var mapSlice = make([]map[string]unit, 0) //0 is initial size

mapSlice = append(mapSlice, userData)

```
