﻿# GitPractice
const inserSort =  (arr)=>{
  
  for (let i =1; i < arr.length;i++){
    const curr = arr[i]
    let j = i -1
    while(j>=0 && arr[j]> curr){
      arr[j+1] = arr[j]
      j--
    }
    arr[j+1]= curr    
  }
  return arr
}

inserSort([1,3,5,9,7])
