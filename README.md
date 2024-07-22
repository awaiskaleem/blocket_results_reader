# Blocket Kia Reader

1. Enter your preferences in following URL: `https://www.blocket.se/bilar/sok?filter={"key":"make","values":["Kia"]}&filter={"key":"models","values":["Optima"]}&filter={"key":"modelYear","range":{"start":"2018","end":"2019"}}&filter={"key":"milage","range":{"start":"10000","end":"15000"}}&filter={"key":"fuel","values":["Miljöbränsle/Hybrid"]}`. I had it for Kia Optima 2018-2019 for specific mileage.
2. Go to results and copy element where all results are selected, copy each page to `data` folder (not created here). Name them as `blocket.data1/2/3...`
3. Run the code and get result in `car_listings.csv`
