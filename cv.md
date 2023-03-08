
# Andrey Golovanyuk
## Personal Data:
* **Address:** Jaroslavl-city, Russia
* **Date of birth:** 29.10.1985
* **Phone:** +7-920-118-23-96                       
* **E-mail:** maven23@rambler.ru
* **GitHub:** Mvnmv2
## Education:
*2002-2007 --*   Yaroslavl State University/industrial and civil engineering

*2022      --*   Plekhanov Russian University of Economics/Java Fullstack Dvrloper

## Skills :
* *Html*, *CSS*, *JavaScript*
* *React*
* *Basics Java and Spring*
* *Basics Php and Laravel* 
## Code example:
A classic algorithm for searching for an element in a sorted array using splitting the array into halves
```
function binarySearch(arr, num){
				
				let low = 0
				let high = arr.length - 1 

				while(low <= high) {
					let mid = Math.floor((high - low)/2) + low
					if(num === arr[mid]){
						return mid
						} else if (num > arr[mid]){
						low = mid + 1
						continue
						} else if (num < arr[mid]) {
						high = mid - 1
						continue
					} 
				}
				return null
			}
```
## English
**A1**