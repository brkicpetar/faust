# Faust
Faust je softver napravljen za **grafički studio GAMA, Beograd**. Namenjen je ubrzanju rada automatizovanjem određenih poslova.  

U sebi sadrži više manjih programa. U svakodnevnom radu se pokazalo da ga ubrzava i do **10X**.

Preporučuje se da se ovaj softver koristi kroz **Total Commander**. Sve opcije će se nalaziti u **vertical baru**.  
Setup će automatski podesiti Vaš **Total Commander** kako biste mogli da koristite ovaj program što jednostavnije.

![faust 4](https://user-images.githubusercontent.com/40390033/149665176-59817cd8-3f27-4f3d-875d-285623fe54dc.png)

## INI Setup

Svi programi koriste podatke iz **INI (konfiguracionih) fajlova**. Njima upravlja **INI Setup**.

<img src="https://user-images.githubusercontent.com/40390033/149665017-e44e0dd3-636c-4110-a8c8-55f7afc609d9.png" width="30%"></img> <img src="https://user-images.githubusercontent.com/40390033/149665015-2a629391-89ad-4ec8-9bd1-6216d8ca4842.png" width="30%"></img> <img src="https://user-images.githubusercontent.com/40390033/149665016-7dfc88dd-2184-4289-8497-7bab29ab4cbc.png" width="30%"></img>   

Prva strana INI Setupa je povezana sa **osnovnim podešavanjima**, kao na primer specifičnim putanjama itd.  
Druga strana INI Setupa je povezana sa **vrstama i veličinama štamparskih ploča** koje se koriste u radu.  
Treća strana INI Setupa is povezana sa **informacijama o klijentima**.

## Dimenzije fajlova

Ovaj program izlistava sve **PDF i PS (PostScript) fajlove** koje se nalaze na udaljenoj lokaciji u folderu sa današnjim danom.
Prikazuje njihove **MediaBox**, **CropBox** i **TrimBox** dimenzije, kao i ukupne brojeve strana.  
Program će ispisati upozorenje ukoliko neki od fajlova ima različite dimenzije strana. Potom će pružiti priliku da korisnik proveri veličinu svake strane.   
<img src="https://user-images.githubusercontent.com/40390033/149665308-245f95bb-20b4-4c98-8de9-1c37ee6e9655.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/40390033/149665334-29164f74-451c-44cb-bd11-e5000e7014b1.png" width="28%" height="28%"></img>  

## Dizanje na ploču

Ovaj program menja sve **PageBox** dimenzije na dimenzije štamparske ploče ("podiže ih na ploču").
Ukoliko program može da odredi koju ploču koristi klijent, automatski će odabrati potrebne dimenzije.  
U suprotnom, program će od koristnika zahtevati da izabere određenu ploču, ukoliko klijent štampa na više od jedne dimenzije, ili da sam unese dimenzije ploča, ukoliko ne postoje odgovarajući podaci o klijentu.

<img src="https://user-images.githubusercontent.com/40390033/149665541-dc32213d-2228-4075-9bd7-b6358aa0bfb3.png" width="45%"></img> 
<img src="https://user-images.githubusercontent.com/40390033/149665543-59989cc7-a6d2-4cb3-a3a0-ff8c9ebf3a5d.png" width="45%"></img> 

## Prebacivanje u kućice ploča

Ovaj program prebacuje sve **.TIFF** i **.TIF** fajlove u određene foldere. Detektuje u koji folder fajl treba da se prebaci na osnovu imena tog fajla.  
Ovaj program poseduje i **"progress bar"**, kako bi se vizuelno predstavilo koliki procenat posla je izvršen.  

<img src="https://user-images.githubusercontent.com/40390033/149665752-0e79070a-d7ac-4a70-bf55-55ccf456ba74.png" width="45%"></img> 


## Ostali programi
Ovaj softver poseduje i još par ostalih programa koji prebacuju/kopiraju fajlove/foldere na predodređene lokacije. Ne poseduju grafički interfejs, tako da se sav posao odvija **"iza kulisa"**.
Neki od ovih programa reimenuju fajlove na osnovu precizno određene konvencije imenovanja.

## Često postavljana pitanja
**Q**: Gde se nalazi source code?  
**A**: Za delove koda me možete kontaktirati na email priložen na mom GitHub profilu.  
**Q**: U kom programskom jeziku je ovaj softver napisan?  
**A**: Ceo program je napisan u programskom jeziku **C#**.  
**Q**: Koja licenca pokriva ovaj softver?  
**A**: Ovaj softver potpada pod **3-Clause BSD Licencu**.  

