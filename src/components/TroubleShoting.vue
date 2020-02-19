<template>
  <div class="troubleShoting">
     
      <h4 class="qOne">
          <b>
           Troubleshooting
          </b>
          </h4>
      

      <b-card>
      <b>
      <p class="qOne"> I don't receive landline calls on my Wavephone Dialer but I can make outgoing calls.</p>
      </b>
      <p>Change your extention number. Choose a QR card that isn't marked "Outgoing calls only", If you are sure that you QR card 
      doesn't have that mark, then your phone may be blocking notifications to Wavephone Dialer. Go to Android > Setting > 
      Apps > Wavephone Dialer > Notification. Select Emergency.</p>
      </b-card>

      <br>
      <b-card>

      <p class="qOne"><b>I can neither make nor receive landline calls on my Wavephone Dialer.</b></p>
      <p>Make sure your Wavephone Dialer is connected to the Internet. if Wavephone Dialers on other phones also have this 
      problem, then make sure your base unit has Internet connection and is securely connected to your landline.</p>
      </b-card>

      <br>
      <b-card>

      
      <p class="qOne"><b>None of our extensions can make or receive landline calls.</b></p>
      <p>Make sure that all your phones have internet connection. Also make sure that the base until is on, has Internet and has a 
      landline securely connected to it. The corresponding LEDs will tell you if none,  one or more are missing.</p>
      </b-card>
      <br>
      <b-card>

    
      <p class="qOne"><b>I am unable to make call using the Wifi phone.</b></p>
      <p>Make sure the your Wifi phone is connected to the Internet. If you are able to call other entensions but unable to call a 
      landline number, make sure your base unit is securely connected to your landline. The LINE LED on your base unit should be 
      lit up.</p>
      </b-card>

      <br>
      <b-card>

    
      <p class="qOne"><b>I am unable to make a call using the analog phone.</b></p>
      <p>Make sure the your analog phone is securely connected to the base unit. If your unable to call other extensions, make sure 
      that your base unit is connected to the Internet. The Internet LED on your base unit should be blinking. if your are unable to  
      call a landline number, make sure your base unit is securely connected to your landline. The LINE LED on your base unit 
      should be lit up.</p>
      </b-card>
      <br>
      <b-card>


      <p class="qOne"><b>I don't hear a dial tone on the analog phone.</b></p>
      <p>Make sure the your analog phone is securely connected to the base unit.</p>
      </b-card>

      <br>
      <b-card>

      
      <p class="qOne"><b>I can barely hear the voice of the caller when using Wavephone Dialer.</b></p>
      <p>If increasing the volume of your smartphone isn't enough, you can increase the playback boost in the app Setting > 
      Preffereces > Sound. Note that on some phonesm increasing the playback boost too much may adversely affect the quality of
      the sound you hear. The ideal setting varies from phone to phone.</p>
      </b-card>
      <br>
      <b-card>

      
      <p class="qOne"><b>I am unable to scan the  QR code shown on the QR card.</b></p>
      <p>Some phones may experience this problem. Reboot your phone and try again. If that doesn't work, you may scan the QR card 
      using a 3rd-party QR scanner app, from another phone if necessary, then manually type the username and password on your 
      Wavephone Dialer.</p>
      </b-card>

      <br>
      <b-card>

      
      <p class="qOne"><b>I get an 'Account not found' error when I register my Wavephone Dialer using a QR card.</b></p>
      <p>This can be a  temporary glitch in your network. You can try connecting to a different network like your 4G/LTE network, 
      then try again.</p>
      </b-card>
  </div>
</template>

<script>
export default {
    name:"troubleShoting",
    
}
</script>

<style scoped>
.cardbg{
   background-color: #2aabdf;
}

.qOne{
    color: #5696c1;
}
</style>