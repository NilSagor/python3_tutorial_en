


// start function seatarrangement(seatnumber)
	x = [[[1, 2, 3], [4, 5, 6]], [[12, 11, 10], [9, 7, 8]] ]

if input_seat to checkking seat number   difference  is 11 or 1 is window seat
ws = [1, 11]
if input_seat to checkking seat number   difference  is 9 or 3 is Middle seat
ms = [3, 9]
if input_seat to checkking seat number   difference  is 7 or 4 is Aisle seat
as = [4, 7]
//loop through row
for x in range(len(x)):
	//loop through column:
	for j in range(len(x)):
    	// check difference of seatnumber to matrix loop row and column , if it is
			//print rowcolumn number and difference variable