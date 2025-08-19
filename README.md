# inputting-no.-and-then-creating-array-till-that-no.-and-finding-factorial-of-elements-in-array.js
//js of inputting no. and then creating array till that no. and finding factorial of the elements in array.
n=prompt("enter the no.=");
let arr=[];
for(i=1;i<n;i++)
     arr[i-1]=i;
console.log(arr);
let factorial=arr.reduce((prev,val)=>{
    return prev*val;
});
console.log(factorial);
