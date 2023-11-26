<template>
    <div class="card">
            <div class="section-1">
              <div class="dot1"></div>
              <div class="dot2"></div>
              <div class="dot3"></div>
              <div class="dot4"></div>
            </div>
            <div class="card-content">
              <button  class="dropdown-btn"  onclick="toggleDropdown()"></button>
              <p >Name</p>
              <p>Address</p>
              <p>Delivery</p>
            </div>
              <div class="RelatedInfo">
              <p>Ch.agan Preetam</p>
              <p>H.No. 6-1-859,New Thi....</p>
              <p>4</p>
              </div>
              <div class="img1"><img src="../assets/bottlelogo.png"/></div>
              <div style="width: 379px; height: 18px; left: 4px; top: 110px; position: absolute">
                  <div style="width: 420px; height: 14px; left: 0px; top: 0px; position: absolute; background: #FF8383; border-radius: 5px"></div>
                  <div style="left: 29px; top: 2px; position: absolute; color: white; font-size: 10px; font-family: Poppins; font-weight: 500; word-wrap: break-word">No Sugar ,ginger,tomato</div>
                  <img style="width: 10px; height: 10px; left: 16px; top: 2px; position: absolute" src="https://via.placeholder.com/10x10" />
              </div>
         </div>
  </template>
  <style>
    .card {
      position: absolute;
        top: 12%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 450px;
         height: 130px;
         border: 1px solid #ccc;
         border-radius: 8px;
         overflow: hidden;
         box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
         margin: 20px;
         display: flex;
    }
    .section-1{
      left: 19px; top: 50px; position: absolute;
    }
    .card-content {
      align-items: flex-start;
      padding-left: 15%;
      text-align: left;
      text-decoration-style: solid black;
      font-family: Poppins; 
      font-weight: 600;
       word-wrap: break-word;
    }
  
    .RelatedInfo {
      margin-top:2%;
      align-items: flex-start;
      padding-left: 5%;
      text-align: left;
      width: 117px; 
      text-decoration-style: solid black;
      font-size: 12px; 
      font-family: Montserrat; 
      font-weight: 500; word-wrap: break-word;
      }
    .dropdown-btn {
      
      padding: 10px;
      border-radius: 0px;
      cursor:pointer;
      border: solid black;
      border-width: 0 3px 3px 0;
      display: inline-block;
      position:absolute;
      right: 30px;
      top: 40%;
      transform: rotate(45deg);
      -webkit-transform: rotate(45deg);
      }
    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      min-width: 160px;
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
      z-index: 1;
    }
  
    .dropdown-content a {
      color: black;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
      align-items: left;
    }
  
    .dropdown-content a:hover {
      background-color: #f1f1f1;
  
    }
  
      .dot1 {
        
        width: 10px; height: 10px; left: 0px; top: 0px; position: absolute; background: #FEBA02; box-shadow: 0px 4px 4px rgba(66.30, 66.30, 66.30, 0.25) inset; border-radius: 9999px;
      }
  
    .dot2{
      width: 10px; height: 10px; left: 0px; top: 12px; position: absolute; background: #FEBA02; box-shadow: 0px 4px 4px rgba(66.30, 66.30, 66.30, 0.25) inset; border-radius: 9999px;
                      
    }
    .dot3{
      width: 10px; height: 10px; left: 14px; top: 0px; position: absolute; background: #FEBA02; box-shadow: 0px 4px 4px rgba(66.30, 66.30, 66.30, 0.25) inset; border-radius: 9999px;
                     
    }
    .dot4{
      width: 10px; height: 10px; left: 14px; top: 12px; position: absolute; background: #FEBA02; box-shadow: 0px 4px 4px rgba(66.30, 66.30, 66.30, 0.25) inset; border-radius: 9999px;
    }
    .img1 {
      padding: 25px;
      left: 296px; 
      top: 8px;
      position: absolute
       }
  
   
  </style>
  
  
  
  
  
  
    
    