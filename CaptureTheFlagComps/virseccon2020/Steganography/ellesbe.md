# 80 POints
```
Ah, bonjour mon bon ami! Bienvenue à la capture du drapeau! J’ai entendu dire que vous étiez fan de la stéganographie! Avez-vous déjà entendu parler d’un outil appelé zsteg?

Download the file below:

```
- tried loads of things stegsolve.jar, steghide, etc... then decided to translate the string above. It reads:
```
Ah, hello my good friend! Welcome to the capture of the flag! I heard you were a fan of steganography! Have you ever heard of a tool called zsteg
```

Cool! let's get zsteg..
`gem install zsteg`

then as i don't know how to use it.
`zsteg --help`
then thought let's try all..
`zsteg -a elessbe.png`
and look!! on `b1,bgr,lsb,xy` layer we get the flag!

FLAG: 
`LLS{lsb_est_mon_bon_ami}`