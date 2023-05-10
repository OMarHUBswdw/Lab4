<!DOCTYPE html>
<html>
<head><meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<script>
let eded1 = parseInt(prompt("eded1: "));
let eded2 = parseInt(prompt("eded2: "));
let cem = 0;
let hasil = 1;

while (eded1 <= eded2){
    if (eded1%19 == 0) {cem+=eded1; hasil*=eded1;}
    eded1++;
}
if(hasil==1){
    alert("cem: "+cem+"\nhasil: 0");
}
    
else {
    alert("cem: "+cem+"\n hasil: "+hasil);
}
</script>
</head></html>

