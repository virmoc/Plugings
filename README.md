# Plugings

Live Server

Prettier

HTML CSS Support  (Hungarian Language Pack for VS Code)

Start git-bash

git History

jsHint

markDown PDF

Babel ES6/Es7

Docker

Thunder Client

-----------------------------------

*git bash-ba minden előtt, biztos ami biztos*

composer install

npm install

cp .env.example .env

php artisan key:generate

php artisan serve


-----------------------------------


php artisan make:controller BejegyzesFelvitelController

php artisan model make:Bejegyzes -m -> létrehozza a táblát de csak ha van -m

php artisan optimize

php artisan serve  

php artisan migrate

-----------------------------------

https://github.com/virmoc/probavizsga_kiindulo

-----------------------------------

nem módosítható, de bejárható -> iterable

saját kivétel kezelés -> Exception

sorbarendezés -> comparator

Collator, getInstance -> ékezet

Comparator -> amit rendezni akarsz ahhoz, kell neki static

mentés -> try catch, 

  try {
            ObjectOutputStream objKi = new ObjectOutputStream(new FileOutputStream("galeria.bin"));
            objKi.writeObject(galeria);
            objKi.close();
        } catch (FileNotFoundException ex) {
            Logger.getLogger(Program.class.getName()).log(Level.SEVERE, null, ex);
        } catch (IOException ex) {
            Logger.getLogger(Program.class.getName()).log(Level.SEVERE, null, ex);
        }
        
            
végén null, 

            galeria = null;
            
            
utána beolvoasni

            try {
            ObjectInputStream objBe = new ObjectInputStream(new FileInputStream("galeria.bin"));
            galeria = (Galeria)objBe.readObject();
            
            objBe.close();
            
            System.out.println("Visszaállítás:");
            for (KiallitasiTargy targy : galeria) {
                System.out.println(targy);
            }
            

másolható -> cloneable
