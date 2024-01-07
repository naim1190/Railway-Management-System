<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>Railway.Management</title>
    <link rel="stylesheet" href="mystyle.css">
</head>
<body>
    <!--Header part start-->
    <header>
        <div class="logo">
            <img src="Railway logo.jpg">
        </div>
        
        <div class="heading">
            Bangladesh Railway
        </div>
        <div class="navbar">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Login</a></li>
                <li><a href="#">Register</a></li>
                <li><a href="#">Station Information</a>
                <ul>
                    <li>Chittagong</li>
                    <li>Dhaka</li>
                    <li>Sylhet</li>
                    <li>Cumilla</li>
                </ul>
                </li>
                <li><a href="#">Services</a>
                <ul>
                        <li>Train Schedule</li>
                        <li>Station Information</li>
                        <li>Buy Ticket</li>
                    </ul>
                </li>
                <li><a href="#">Contact Us</a>
                <ul>
                    <li>01833-515057 (Naim)</li>
                    <li>01884-055866 (Sham)</li>
                    <li>01952-332506 (Ratul)</li>
                    <li>01867-939450 (Sagor)</li>

                </ul>
                </li>
                

            </ul>
        </div>
    </header>
    <hr style="color:aquamarine;">
    <br><br><br>
    <!--Header part end-->
    
    <div class="formD">
    <form>
        <label for="station">From:</label>
        <input list="sta" style="font-size: 20px;" placeholder="Select Station">
        <datalist id="sta">
            <option value="Chittagong"></option>
            <option value="Dhaka"></option>
            <option value="Cumilla"></option>
            <option value="Sylhet"></option>

</datalist> 
                <label for="station">To:</label>
                <input list="sta" style="font-size: 20px;" placeholder="Select Station">
                <datalist id="sta">
                    <option value="Chittagong"></option>
                    <option value="Dhaka"></option>
                    <option value="Cumilla"></option>
                    <option value="Sylhet"></option>
                </datalist> <br> <br>
                
                <label for="date">Date of Journey:</label> <br>
                <input type="date" id="date" style="font-size: 25px;" placeholder="pick a date"> <br><br>

                <label for="seat">Choose a class:</label><br>
                <input list="seat" style="font-size: 20px;" placeholder="choose a class">
                <datalist id="seat">
                    <option value="AC_B"></option>
                    <option value="AC_S"></option>
                    <option value="SNIGDHA"></option>
                    <option value="F_BERTH"></option>
                    <option value="F_SEAT"></option>
                    <option value="F_CHAIR"></option>
                    <option value="S_CHAIR"></option>
                    <option value="SHOVAN"></option>
                    <option value="SHULOV"></option>
                    <option value="AC_CHAIR"></option>
                </datalist>
                

    </form>
    
    </div><br>
    <div class="search">SEARCH TRAIN</div> 
    
    <!--Seat start-->
    <div class="plane">
        <div class="select">
          <h1>Please select a seat</h1>
        </div>
        <div class="exit"></div>
      <ol>
        <li>
          <ol class="seats">
            <li class="seat">
              <input type="checkbox" id="1A" />
              <label for="1A">1A</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="1B" />
              <label for="1B">1B</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="1C" />
              <label for="1C">1C</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="1D" />
              <label for="1D">1D</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="1E" />
              <label for="1E">1E</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="1F" />
              <label for="1F">1F</label>
            </li>
          </ol>
        </li>
        <li>
          <ol class="seats">
            <li class="seat">
              <input type="checkbox" id="2A" />
              <label for="2A">2A</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="2B" />
              <label for="2B">2B</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="2C" />
              <label for="2C">2C</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="2D" />
              <label for="2D">2D</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="2E" />
              <label for="2E">2E</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="2F" />
              <label for="2F">2F</label>
            </li>
          </ol>
        </li>
        <li>
          <ol class="seats">
            <li class="seat">
              <input type="checkbox" id="3A" />
              <label for="3A">3A</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="3B" />
              <label for="3B">3B</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="3C" />
              <label for="3C">3C</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="3D" />
              <label for="3D">3D</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="3E" />
              <label for="3E">3E</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="3F" />
              <label for="3F">3F</label>
            </li>
          </ol>
        </li>
        <li>
          <ol class="seats">
            <li class="seat">
              <input type="checkbox" id="4A" />
              <label for="4A">4A</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="4B" />
              <label for="4B">4B</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="4C" />
              <label for="4C">4C</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="4D" />
              <label for="4D">4D</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="4E" />
              <label for="4E">4E</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="4F" />
              <label for="4F">4F</label>
            </li>
          </ol>
        </li>
        <li>
          <ol class="seats">
            <li class="seat">
              <input type="checkbox" id="5A" />
              <label for="5A">5A</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="5B" />
              <label for="5B">5B</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="5C" />
              <label for="5C">5C</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="5D" />
              <label for="5D">5D</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="5E" />
              <label for="5E">5E</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="5F" />
              <label for="5F">5F</label>
            </li>
          </ol>
        </li>
        <li>
          <ol class="seats">
            <li class="seat">
              <input type="checkbox" id="6A" />
              <label for="6A">6A</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="6B" />
              <label for="6B">6B</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="6C" />
              <label for="6C">6C</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="6D" />
              <label for="6D">6D</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="6E" />
              <label for="6E">6E</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="6F" />
              <label for="6F">6F</label>
            </li>
          </ol>
        </li>
        <li>
          <ol class="seats">
            <li class="seat">
              <input type="checkbox" id="7A" />
              <label for="7A">7A</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="7B" />
              <label for="7B">7B</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="7C" />
              <label for="7C">7C</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="7D" />
              <label for="7D">7D</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="7E" />
              <label for="7E">7E</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="7F" />
              <label for="7F">7F</label>
            </li>
          </ol>
        </li>
        <li>
          <ol class="seats">
            <li class="seat">
              <input type="checkbox" id="8A" />
              <label for="8A">8A</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="8B" />
              <label for="8B">8B</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="8C" />
              <label for="8C">8C</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="8D" />
              <label for="8D">8D</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="8E" />
              <label for="8E">8E</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="8F" />
              <label for="8F">8F</label>
            </li>
          </ol>
        </li>
        <li>
          <ol class="seats">
            <li class="seat">
              <input type="checkbox" id="9A" />
              <label for="9A">9A</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="9B" />
              <label for="9B">9B</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="9C" />
              <label for="9C">9C</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="9D" />
              <label for="9D">9D</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="9E" />
              <label for="9E">9E</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="9F" />
              <label for="9F">9F</label>
            </li>
          </ol>
        </li>
        <li>
          <ol class="seats">
            <li class="seat">
              <input type="checkbox" id="10A" />
              <label for="10A">10A</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="10B" />
              <label for="10B">10B</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="10C" />
              <label for="10C">10C</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="10D" />
              <label for="10D">10D</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="10E" />
              <label for="10E">10E</label>
            </li>
            <li class="seat">
              <input type="checkbox" id="10F" />
              <label for="10F">10F</label>
            </li>
          </ol>
        </li>
      </ol>
      <div class="exit"></div>
    </div>
    
    <!--Seat End-->
    <hr style="color: bisque;">
    <div class="img">
        <img src="https://1000logos.net/wp-content/uploads/2021/02/Bkash-logo.png">
        <img src="https://download.logo.wine/logo/Nagad/Nagad-Logo.wine.png">
        <img src="https://play-lh.googleusercontent.com/cCVvEEwDQSPmDO8F-kryWhvzy53JllG1FGtHGDG-SDgfVTvvYSvWEXXDbgAY0hf7Bg">
        <img src="https://seeklogo.com/images/D/dutch-bangla-rocket-logo-B4D1CC458D-seeklogo.com.png">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Mastercard-logo.svg/2560px-Mastercard-logo.svg.png">
       <img src="https://branditechture.agency/brand-logos/wp-content/uploads/wpdm-cache/Visa-Payment-Card-900x0.png">
       <img src="https://hostmight.com/assets/images/dbbl.png">
    </div>
    
    <hr style="color: bisque;">
    
    <!--Footer Start-->
    
    <footer>
        <hr style="color:aquamarine;">
        <div class="foot">
            <h2>Bangladesh Railway</h2>

        </div>
        <div class="text">
            <p>The tickets are issued by Bangladesh Railway Integrated Ticketing System (BRITS) and premier university's CSE 42<sup>nd</sup> Batch Student is responsible for designing, development, implementation, technical operation & maintenance of the system.</p> 

        </div>
        <div class="icon">
            <i class="fa fa-facebook"></i>
            <i class="fa fa-twitter"></i>
            <i class="fa fa-linkedin"></i>
            <i class="fa fa-youtube"></i>
    </div>

    <div class="copyright">
        Copyright @2024 Premier University
    </div>
    </footer>
    <!--Footer End-->


</body>
</html>
