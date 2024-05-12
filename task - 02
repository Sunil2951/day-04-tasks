
    //Print odd numbers in an array
    var odd=(arr)=>{
        var a=[];
            for(var i=0;i<arr.length;i++){
                 if(arr[i]%2==1){
                a.push(arr[i]);
             }
         }
         return a;
     }


     //Convert all the strings to title caps in a string array
         var titlecaps=(str)=>{
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
         var sum=(arr)=>{
          var a=0;
          for(var i=0;i<arr.length;i++){
            a=a+arr[i];
          }
          return a;
         }


         //Return all the prime numbers in an array
         var prime=(arr)=>{
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
          var palindrome=(arr)=>{
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
         
         console.log(odd([1,3,4,8,9,2]));
         console.log(titlecaps('sunil joshi in guvi'));
         console.log(sum([7,5,3,8,6,9,2]))
         console.log(prime([7,5,3,8,6,9,2]));
         console.log(palindrome(["guvi","madam","sunil","noon","rotator"]));
         



