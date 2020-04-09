### PreCamp # 6
Surasak somboon

### (5.Object-Oriented Javascript)
Lab OPP

ภาพโจทย์ Link ::>>>>>    https://docs.google.com/presentation/d/1R2Aur4xmZmsuCcRUTDuPsL5TDO9JH1tyrYRAqkMZ4Bo/edit#slide=id.g7ca3c3f386_0_54


Response...

class userTemp {

    constructor (name,pass,age,dateTime){
    this.name = name;
    this.pass = pass;
    this.age = age;
    this.connected = false;
    
    this.logOut = true;
    this.dateTime = dateTime;
    }

    login(){
        this.connected = true;
        this.logOut = false;
        console.log('login status : ',this.connected)
    }

    logout(){
        this.connected = false;
        this.logOut = true;
        console.log('LogOut status : ',this.logOut)
    }

    checkStatus(){
        if (this.connected === true){
            console.log("ตอนนี้อยู่ในสถานะ Login :]")
        } else {
            console.log("ตอนนี้อยู่ในสถานะ LogOut :]")
        }

    }

}
