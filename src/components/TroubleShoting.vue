<template>
  <div class="troubleShoting">
     
      <h4 class="qOne">
          <b>
           Troubleshooting
          </b>
          </h4>

          <b-card v-b-toggle.accordion-1  class=" btn-col pointer">
           <p class="qOne pointer btn-link"  > 
                <b>
         I don't receive landline calls on my Wavephone Dialer but I can make outgoing calls.
                </b>
            </p>
      
      <b-collapse id="accordion-1"  accordion="my-accordion" role="tabpanel">
          <p>Change your extention number. Choose a QR card that isn't marked "Outgoing calls only", If you are sure that you QR card 
      doesn't have that mark, then your phone may be blocking notifications to Wavephone Dialer. Go to Android > Setting > 
      Apps > Wavephone Dialer > Notification. Select Emergency.</p>
      </b-collapse>
    </b-card>
          


    

      <br>

      <b-card v-b-toggle.accordion-2  class=" btn-col pointer">
           <p class="qOne pointer btn-link"  > 
                <b>
         I can neither make nor receive landline calls on my Wavephone Dialer.
                </b>
            </p>
      
      <b-collapse id="accordion-2"  accordion="my-accordion" role="tabpanel">
          <p>Make sure your Wavephone Dialer is connected to the Internet. if Wavephone Dialers on other phones also have this 
      problem, then make sure your base unit has Internet connection and is securely connected to your landline.</p>
      </b-collapse>
    </b-card>
    <br>


     <b-card v-b-toggle.accordion-3 class=" btn-col pointer">
           <p class="qOne pointer btn-link"  > 
                <b>
                    None of our extensions can make or receive landline calls.
                </b>
            </p>
      
      <b-collapse id="accordion-3"  accordion="my-accordion" role="tabpanel">
          <p>Make sure that all your phones have internet connection. Also make sure that the base until is on, has Internet and has a 
      landline securely connected to it. The corresponding LEDs will tell you if none,  one or more are missing.</p>
      </b-collapse>
    </b-card>



      <br>


      <b-card v-b-toggle.accordion-4 class=" btn-col pointer">
           <p class="qOne pointer btn-link"  > 
                <b>
                    I am unable to make call using the Wifi phone.
                </b>
            </p>
      
      <b-collapse id="accordion-4"  accordion="my-accordion" role="tabpanel">
          <p>Make sure the your Wifi phone is connected to the Internet. If you are able to call other entensions but unable to call a 
      landline number, make sure your base unit is securely connected to your landline. The LINE LED on your base unit should be 
      lit up.</p>
      </b-collapse>
    </b-card>


      <br>

      <b-card v-b-toggle.accordion-5 class=" btn-col pointer">
           <p class="qOne pointer btn-link"  > 
                <b>
                   I am unable to make a call using the analog phone.
                </b>
            </p>
      
      <b-collapse id="accordion-5"  accordion="my-accordion" role="tabpanel">
           <p>Make sure the your analog phone is securely connected to the base unit. If your unable to call other extensions, make sure 
      that your base unit is connected to the Internet. The Internet LED on your base unit should be blinking. if your are unable to  
      call a landline number, make sure your base unit is securely connected to your landline. The LINE LED on your base unit 
      should be lit up.</p>
      </b-collapse>
    </b-card>
    <br>
     <b-card v-b-toggle.accordion-6 class=" btn-col pointer">
           <p class="qOne pointer btn-link"  > 
                <b>
                  I don't hear a dial tone on the analog phone.
                </b>
            </p>
      
      <b-collapse id="accordion-6"  accordion="my-accordion" role="tabpanel">
          <p>Make sure the your analog phone is securely connected to the base unit.</p>
      </b-collapse>
    </b-card>

    

      <br>


      <b-card v-b-toggle.accordion-7 class=" btn-col pointer">
           <p class="qOne pointer btn-link"  > 
                <b>
                 I can barely hear the voice of the caller when using Wavephone Dialer.
                </b>
            </p>
      
      <b-collapse id="accordion-7"  accordion="my-accordion" role="tabpanel">
          <p>If increasing the volume of your smartphone isn't enough, you can increase the playback boost in the app Setting > 
      Preffereces > Sound. Note that on some phonesm increasing the playback boost too much may adversely affect the quality of
      the sound you hear. The ideal setting varies from phone to phone.</p>
      </b-collapse>
    </b-card>


      <br>

      <b-card v-b-toggle.accordion-8 class=" btn-col pointer">
           <p class="qOne pointer btn-link"  > 
                <b>
                I am unable to scan the  QR code shown on the QR card.
                </b>
            </p>
      
      <b-collapse id="accordion-8"  accordion="my-accordion" role="tabpanel">
          <p>Some phones may experience this problem. Reboot your phone and try again. If that doesn't work, you may scan the QR card 
      using a 3rd-party QR scanner app, from another phone if necessary, then manually type the username and password on your 
      Wavephone Dialer.</p>
      </b-collapse>
    </b-card>

      <br>

      <b-card v-b-toggle.accordion-9 class=" btn-col pointer">
           <p class="qOne pointer btn-link"  > 
                <b>
                I get an 'Account not found' error when I register my Wavephone Dialer using a QR card.
                </b>
            </p>
      
      <b-collapse id="accordion-9"  accordion="my-accordion" role="tabpanel">
          <p>This can be a  temporary glitch in your network. You can try connecting to a different network like your 4G/LTE network, 
      then try again.</p>
      </b-collapse>
    </b-card>

     

      
  </div>
</template>

<script>
export default {
    name:"troubleShoting",
    
}
</script>

<style scoped>


.qOne{
    color: #5696c1;
}



.btn-width{
    font-size: 16px;
    width: 100%;
    background-color: white;
}

.pointer {cursor: pointer;}


</style>