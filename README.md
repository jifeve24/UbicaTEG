# UbicaTEG
primer comit


proyecto Universidad Huella

EXEC sp_configure 'show advanced options', 1
RECONFIGURE
GO


EXEC sp_configure 'xp_cmdshell', 1
RECONFIGURE
GO

GRANT EXECUTE ON xp_cmdshell TO [Domain\TestUser]

USE master;
GRANT CONTROL SERVER TO [Domain\TestUser]
GO




VB

Sub PlayBackgroundSoundFile()
    My.Computer.Audio.Play("C:\Waterfall.wav", 
        AudioPlayMode.WaitToComplete)
End Sub


En el ejemplo siguiente, el método de My.Computer.Audio.Play reproduce un sonido.Al utilizar este ejemplo, debe asegurarse de que los recursos de la aplicación incluyen un archivo de sonido .wav denominado Waterfall.
VB
Sub PlayBackgroundSoundResource()
    My.Computer.Audio.Play(My.Resources.Waterfall, 
        AudioPlayMode.WaitToComplete)
End Sub



fondos
https://www.google.hn/search?q=fondos+para+programas&biw=1024&bih=663&source=lnms&tbm=isch&sa=X&ved=0ahUKEwibyaXU2_XLAhUGXh4KHZnpCScQ_AUIBigB#tbm=isch&q=fondos+windows+10+flat&imgrc=4XtMhHaP0-MJkM%3A

http://www.lirent.net/2014/10/download-material-design-wallpapers-android-lollipop/
http://www.lirent.net/2014/11/new-android-wallpapers-with-lollipop-material-design/
http://www.lirent.net/2014/10/download-android-lollipop-wallpapers-material-design/

iconos
-------------
https://www.google.hn/search?q=descargar+iconos+planos&espv=2&biw=1024&bih=663&source=lnms&tbm=isch&sa=X&ved=0ahUKEwiNqe7m3_XLAhXE2B4KHQACASIQ_AUIBigB#tbm=isch&tbs=rimg%3ACe_1HvOZCRIz-IjjDcLnH-UEhCLYzBa_1_1woYH0WQ9Hw_1-3Lo4MJw7TFlWu3In7wMoMdeQ-_1vjLcPmaarQZd2Z0CEhxioSCcNwucf5QSEIER1bps9EmXeEKhIJtjMFr_1_1ChgcR7TABIeATe7QqEgnRZD0fD_17cuhHUeZILwt-PRyoSCTgwnDtMWVa7Eb5NKMIEkE-eKhIJcifvAygx15ARHVqjZPxc3A8qEgn7--Mtw-ZpqhHVa3a9x6kM_1SoSCdBl3ZnQISHGET-FefpVw5O1&q=icon%20flat&imgdii=NWziAgX1jUde3M%3A%3BNWziAgX1jUde3M%3A%3Ba1cS7cNthyc88M%3A&imgrc=NWziAgX1jUde3M%3A

http://www.premiumpixels.com/freebies/flat-file-icons-psd/
http://www.titanui.com/28101-flat-file-type-icon-set-psd/
https://creativevip.net/resource/flat-ms-office-file-icons


------------------------------------

https://dribbble.com/shots/1201666-Free-Flat-Icons
http://www.webhostingsecretrevealed.net/blog/web-design/best-flat-icon-sets-2013/
http://stalker018.deviantart.com/art/MMII-FLAT-icons-Vol-1-376035760
https://www.vectoropenstock.com/vectors/preview/74100/56-computer-long-shadow-circle-icons




-----------------------------------
http://www.mediafire.com/download/s1frr1aooq56q7k/GuardarMostrarImagen.rar





---------------------------------------
https://techperu.wordpress.com/2011/10/24/almacenar-y-mostrar-imagenes-vb-net-sql-server/
PictureBox1.Image = Image.FromFile("C:\image2.jpg")
