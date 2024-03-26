[[.contact-container {
    display:flex;
    height: 110vh;
    align-items: center;
    justify-content: space-evenly; 
    background-color: green;  
    margin-top: 80px; 
    position: relative; 
}
.contact-left{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-right: 40%;
    gap:20px;
     
} 
.contact-left-title h2{
    font-weight:600;
    color:#4b927e;
    font-size: 40px;
    margin-bottom: 5px;
}
  
.contact-inputs{
 width:400px;
 height: 50px;
 border: none;
 outline: none;
 padding-left: 25px;
 font-weight: 500;
 color: pink;
 border-radius: 50px;
}

.contact-left textarea{
    height:140px;
    padding-top: 15px;
    border-radius:20px;
} 
.contact-inputs::placeholder{
    color:grey;
}
.contact-left button{
    display: flex;
    align-items: center;
    padding:  15px 30px;
    font-size: 16px;
    color:grey;
    gap:10px;
    border: none;
    border-radius: 50px;
    background: linear-gradient(270deg, #f5b7dd,#fa6d86);
} 

.contact-right {
    position: absolute; 
    right: 90px;  
    transform: translateY(-50%);
}
.pink-box {
    width: 200px;
    height: 200px;
    background-color: yellow;
    border-radius: 40px;
    transform: rotate(-35deg); 
}

.white-box {
    width: 200px;
    height: 200px;
    background-color: #fff;
    border-radius: 40px;
    transform: rotate(35deg);
    position: absolute;
    right: 50px;  
    top: calc(50% + 210px);  
}]]
**CSS(Cascading Style Sheets): CSS is a computer language used for laying out and structuring web pages.