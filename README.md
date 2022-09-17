# core-code-upskilling-readme

# e01

const reverseStr = (str) =>{
if(str){
let strArray = str.split(" ");
let newStr = "";

        for(let i=strArray.length - 1; i>=0; i--){
            newStr = newStr +" "+ strArray[i];
        }
        return newStr.trim();
    }

}

# e02

const findSmallerInteger = (arrayInt) =>{
return Math.min(...arrayInt);
}

# e03

const findOddOrEven = (arrayInt) => {
let result = 0;
let outPut = "Odd";
if(arrayInt){
arrayInt.forEach((num)=>{
result = result + num;
});
}
if(result % 2 == 0){
outPut = "even";
}
return outPut;
};
