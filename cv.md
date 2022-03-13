### Dmitry Halavach  
***  
#### Skills  
- HTML
- CSS
- Javascript
- Automated Testing (Java)
#### Code Example  
	//Function returning the sum of nested array  
	
	var a1 = [5, 7, [4, [2], 8, [1, 3], 2], [9, []], 1, 8];
	
	function sumNestedArray(i) {
	  var sum = 0;
	  for (var a = 0; a < i.length; a++) {
	    if (typeof i[a] == "number") {
	      sum += i[a];
	    } else if (i[a] instanceof Array) {
	      sum += sumNestedArray(i[a]);
	    }
	  }
	  return sum;
	}
	console.log(sumNestedArray(a1));  
#### English Level  
C2

#### Education
Ph.D. in History (2019)
