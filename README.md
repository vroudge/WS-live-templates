# WS-live-templates

Here are the live templates I always use under Webstorm. Stocked here not to lose them.


### fata - tab - noreformat

    ($start$) => {$end$}
Inserts fat arrow function expression


### func - tab - noreformat

    function $start$($param$){
       $end$
    }
Inserts function expression, either anon or declared


### prm - tab - noreformat

    new Promise((resolve,reject) => {
        $end$
    })
Inserts promise with resolve/reject


### prmt - tab - noreformat

    new Promise(true)
Inserts promise chain start


### then - tab - noreformat

    .then(($start$) => {
        $end$
    })
Inserts then expression for chaining with promises


### if - enter - noreformat

    if($PARAM$){
        $END$
    }
Inserts if expression


### ifelse - enter - noreformat

    if($CONDITION$){
        $IF$
    } else {
        $ELSE$
    }$END$
Inserts if/else expression


### csl - space - noreformat

    console.log('$PARAM$ : ', $PARAM$);
  Inserts console.log with text


### csll - space - noreformat

    console.log($PARAM$);
Inserts console.log without text


