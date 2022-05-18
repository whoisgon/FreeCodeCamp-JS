function telephoneCheck(str) {
  let regex=/1{0,1}\s{0,1}((\(\d{3}\))|(\d{3}))[-]{0,1}[ ]{0,1}\d{3}[- ]{0,1}\d{4}/;
   console.log(str.match(regex));
 
  return regex.test(str) && str.match(regex)[0]===str;
 
}
