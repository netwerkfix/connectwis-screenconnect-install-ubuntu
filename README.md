# connectwise-screenconnect-install<br>
<h2>Works on Ubuntu Desktop 24.04 for me :)</h2>
<h3>To install screenconnect you will need to download first this</h3>
<h4>sudo apt update && sudo apt upgrade -y</h4>
<br><h3>Install the correct dependensie</h3>
<h4>sudo apt install icedtea-netx gdebi-core libminizip1 libxcb-xinerama0 policykit-1 pkexec polkitd polkitd-pkla openjdk-17-jdk curl -y
</h4><br><h3>Install with the Connectwise install script</h3>
<h4>sudo wget https://download1591.mediafire.com/mq7expyrshvgx6-KKt1a7xx7iKArw70Ggo31NYBKxucQC_Afg4lroGknnSIXH-9sit8iIo6z197yhEPX7LcPCdeAGuqzgfU_2mjzwhfhRwhr-qrQD3_1NKydbaxAp03gJLYtdB0tDhQgquBRCTqxoKSwcqzHKNaxzpriCAoDx18/0i8lvryfzfd06nk/ScreenConnect.ClientSetup.sh </h4>
<br>
<h3>Execute this install script</h3>
<h4>sudo chmod 777 ScreenConnect.ClientSetup.sh</h4>
<h4>su localuser</h4>
<h4>./ScreenConnect.ClientSetup.sh</h4>
