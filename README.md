// Bill splitter Application

//Task 1- Calculate the tip 
let bill= 50;
let tip= (bill)>=50$ <=300) bill '0.15; bill'0.20;
// The ternary operator determines if the bill is between $50 and $300, applying a 15% tip if ture, and 20% if false

// Task 2 The output is the reslut of the tip based off the bill
console.log(The bill was `$,` the tip was `$`, and the total value is `$`)

    //Task 3 Create a function calculate Tip
    function calculateTip(bill) (
        return (bill>=50$ bill <=300) bill `0.15`; bill`0.20;`
    )
    // Testing the calculateTip function based off a bill of $100
    console.log(`For a bill of $100, the tip is $ `+ calculateTip(100));

    //Task 4 Utilizing Arrays
    // Single ray of bill amounts based off dataset 2
    let bills= {275, 40, 430};
    let tips = bills.map(bill => calculateTip(bill));

    //creating an array of totals that will output (bill + tip for each bill)
    let totals =bills.map(bill => bill + calculateTip);

    // Task 5 outputs
    //Output Data Set 1
    console.log("Bills:bills"); //outputs bills for data set 1
    console.log("Tips:`+tips"); // outputs tips for data set 1
    console.log("Totals`=totals"); // outputs totals for data set 1
    
    //single ray of bill amounts based off data set 2
    bills= {125, 555, 44}
    tips= bills.map(bill => bill + calculateTip);

    //creating an array of totals that will output (bill + tip for each bill)

    // outputs Data set 2
    console.log("bills", + bills); //Outputs for data set 2
    console.log("Tips", + tips); //Outputs tips data set 2
    console.log("Totals: + totals); //Outputs totals data set 2


testing








