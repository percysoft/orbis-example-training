Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fringilla phasellus faucibus scelerisque eleifend donec pretium vulputate. Volutpat maecenas volutpat blandit aliquam etiam erat. Lorem mollis aliquam ut porttitor. Proin libero nunc consequat interdum varius sit amet mattis vulputate. Faucibus a pellentesque sit amet porttitor eget dolor. Scelerisque varius morbi enim nunc.

Erat imperdiet sed euismod nisi porta. Imperdiet nulla malesuada pellentesque elit eget gravida cum. Velit dignissim sodales ut eu sem integer vitae justo.

Despues de clonar el proycto y cambiar el config de git para que apunte hacia otro repositorio se hizo push al proyecto la cual devolvio un mensaje de error por un supuesto archivo que pesaba mas de 100 mb, para eso mediante la herramienta de gitk verficamos en que commit estaba este problema, al momento de ubicarlo hicimos git reset --hard HEAD~3, previamente se guardo el hash del commit la cual debiamos salvar, una vez hecho el reset hicimos un cherry pick el hash salvado, con los cuales teniamos el commit asociado a ese hash. 


https://bitbucket.org/snippets/orbisunt/rez9zL