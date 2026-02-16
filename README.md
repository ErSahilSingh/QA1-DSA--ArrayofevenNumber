# QA1-DSA--ArrayofevenNumber

function EvenArray(Arr) {
    for (let i = 0; i < Arr.length; i++){
        if (Arr[i] % 2 == 0) {
           console.log("Even No:",Arr[i]) 
        }
    }
}

EvenArray([2,3,6,7,20])
