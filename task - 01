
    //Print odd numbers in an array
    function odd(arr){
        var a=[];
            for(var i=0;i<arr.length;i++){
                 if(arr[i]%2==1){
                a.push(arr[i]);
             }
         }
         return a;
     }


     //Convert all the strings to title caps in a string array
         function titlecaps(str) {
             if ((str === null) || (str === ''))
                 return false;
             else
                 str = str.toString();
          
             return str.replace(/\w\S*/g,
                 function (txt) {
                     return txt.charAt(0).toUpperCase() + txt.substr(1).toLowerCase();
                 });
         }

         //Sum of all numbers in an array
         function sum(arr){
          var a=0;
          for(var i=0;i<arr.length;i++){
            a=a+arr[i];
          }
          return a;
         }


         //Return all the prime numbers in an array
         function prime(arr){
            var a=0;
            var arr1 = [];
            for(var i=0;i<arr.length;i++){
              for(var j=2;j<=arr[i];j++){
                if(arr[i]%j==0)
                  a=a+1;
              }
            if(a==1){
              arr1.push(arr[i]);
              a=0;
            }
            else
            a=0;
            }
            return arr1;
          }

          //Return all the palindromes in an array
          function palindrome(arr){
            var arr1 =[];
            for(var i=0;i<arr.length;i++){
              var a= arr[i].split("");
              a =a.reverse();
              a=a.join("");
              if(arr[i]==a){
                arr1.push(arr[i]);
              }
            }
            return arr1;
          }

          //Return median of two sorted arrays of the same size.

          function compareNumbers(a, b) {
            return a - b;
          }
          function median(arr1,arr2){
            var arr3=[];
            if(arr1.length == arr2.length){
            for(var i=0;i<arr1.length;i++){
              arr3.push(arr1[i]);
              arr3.push(arr2[i]);
              arr3.sort(compareNumbers);
            }
            }
            var n = (arr3.length)/2
           return arr3[n];
          }
          function removeduplicates(arr) {
            return [...new Set(arr)];
        }
        // Rotate an array by k times
        function RightRotate(a, k){ 
          let n = a.length;
          var arr=[];
          var b=0;
        
            k = k % n;
        
            for (let i = 0; i < n; i++) { 
                if (i < k) { 
                  b=(a[n + i - k] + " "); 
                  arr.push(b)
                  b=0;
                } 
                else { 
                  b=(a[i - k] + " "); 
                  arr.push(b);
                  b=0;
                } 
            } 
            return arr;
        } 
         
        
         console.log(odd([1,3,4,8,9,2]));
         console.log(titlecaps('sunil joshi in guvi'));
         console.log(sum([7,5,3,8,6,9,2]))
         console.log(prime([7,5,3,8,6,9,2]));
         console.log(palindrome(["guvi","madam","sunil","noon","rotator"]));
         console.log(median([3,56,89,23,7],[4,65,73,12,9]));
         console.log(removeduplicates(["apple", "mango", "apple","orange", "mango", "mango"]));
         console.log(removeduplicates([2,3,4,5,4,7,3,9,2]));
         console.log(RightRotate([1, 2, 3, 4, 5],2))



