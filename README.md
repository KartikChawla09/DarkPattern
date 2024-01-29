This repositry contains a protoType for DPBH 2024.(currently under development)

The aim of the project is to create an extension which can identify/block dark patterns found on ecommerce website it mainly targets dark pattern such as -> 
1. User Interface Deception.
2. Misleading Product Information.
3. Forced Account Creation.
4. Fake reviews for a product.

First our extension scans for the webpage and create a data file (json) based on the page structure and that data is passed to the model using flask middleware. the model takes in the input 
and classifies that if the given page has any dark pattern found or not.  The prediction given by our model is then returned to the frontend and a count is show for numbers of pattern found on this page 


Here are link for some readings of the project : 
1. [abstract dpbh.pdf](https://github.com/KartikChawla09/DarkPattern/files/14084675/abstract.dpbh.pdf)
2. [dpbh ppt_compressed.pdf](https://github.com/KartikChawla09/DarkPattern/files/14084676/dpbh.ppt_compressed.pdf)  


 <img width="1440" alt="Screenshot 2024-01-29 at 6 41 25 PM" src="https://github.com/KartikChawla09/DarkPattern/assets/95685316/1b51831b-3751-4bac-9128-bbe0396b3b56">
             

