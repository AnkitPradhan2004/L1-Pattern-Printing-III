let N=5;
for(let i=0;i<N;i++){
    let row = "";
    for(let j=0;j<N;j++){
        if(i==0 || i==N-1){
            row += "* ";
        }
        else{
            row="*";
        }
    }
    console.log(row);
}
