<template>
  <div class="troubleShoting">
      <a href=""><h4>Troubleshooting</h4> </a>

      <b-card class="">
      <a href=""> I don't receive landline calls on my Wavephone Dialer but I can make outgoing calls. </a>
      <p>Change your extention number. Choose a QR card that isn't marked "Outgoing calls only", If you are sure that you OR card <br>
      doesn't have that mark, then your phone may be blocking notifications to Wavephone Dialer. Go to Android > Setting > <br>
      Apps > Wavephone Dialer > Notification. Select Emergency.</p>
      </b-card>

      <br>
      <b-card>

      <a href="">I can neither make nor receive landline calls on my Wavephone Dialer.</a>
      <p>Make sure your Wavephone Dialer is connected to the Internet. if Wavephone Dialers on other phones also have this <br>
      problem, then make sure your base unit has Internet connection and is securely connected to your landline.</p>
      </b-card>

      <br>
      <b-card>

      <a href="">None of our extensions can make or receive landline calls.</a>
      <p>Make surethat all your phones have internet connection. Also make sure that the base until is on, has Internet and has a <br>
      landline securely connected to it. The corresponding LEDs will tell you if none,  one or more are missing.</p>
      </b-card>
      <br>
      <b-card>

      <a href="">I am unable to make call using the Wifi phone</a>
      <p>Make sure the your Wifi phone is connected to the Internet. If you are able to call other entensions but unable to call a <br>
      landline number, make sure your base unit is securely connected to your landline. The LINE LED on your base unit should be <br>
      lit up.</p>
      </b-card>

      <br>
      <b-card>

      <a href="">I am unable to make a call using the analog phone.</a>
      <p>Make sure the your analog phone is securely connected to the base unit. If your unable to call other extensions, make sure <br>
      that your base unit is connected to the Internet. The Internet LED on your base unit should be blinking. if your are unable to  <br>
      call a landline number, make sure your base unit is securely connected to your landline. The LINE LED on your base unit <br>
      should be lit up.</p>
      </b-card>
      <br>
      <b-card>

      <a href="">I don't hear a dial tone on the analog phone.</a>
      <p>Make sure the your analog phone is securely connected to the base unit.</p>
      </b-card>

      <br>
      <b-card>

      <a href="">I can barely hear the voice of the caller when using Wavephone Dialer.</a>
      <p>If increasing the volume of your smartphone isn't enough, you can increase the playback boost in the app Setting > <br>
      Preffereces > Sound. Note that on some phonesm increasing the playback boost too much may adversely affect the quality of <br>
      the sound you hear. The ideal setting varies from phone to phone.</p>
      </b-card>
      <br>
      <b-card>

      <a href="">I am unable to scan the  QR code shown on the OR card.</a>
      <p>Some phones may experience this problem. Reboot your phone and try again. If that doesn't work, you may scan the OR card <br>
      using a 3rd-party QR scanner app, from another phone if necessary, then manually type the username and password on your <br>
      Wavephone Dialer.</p>
      </b-card>

      <br>
      <b-card>

      <a href="">I get an 'Account not found' error when I register my Wavephone Dialer using a QR card.</a>
      <p>This can be a  temporary glitch in your network. You can try connecting to a different network like your 4G/LTE network, <br>
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
</style>