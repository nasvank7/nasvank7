
class Nasvan {

    constructor() {
        
        this.alias    = [ 'Nasvan', undefined ]
    }

    contact() {


        const email       = 'nasvank7@@gmail.com'
        const linkedin    = 'https://www.linkedin.com/in/nasvan-k-671771261/'
        
        return  email, linkedin
    }

    life() {


        const age           = 24
        const occupation    = 'Full stack developer'
        const hobbies       = ['Mastering "404" Pages', 'Football']
        
        return age, occupation, hobbies
    }



    programming() {


        const languages     = ['Javascript', 'Typescript']
        const databases     = ['MongoDB', 'Prisma', 'PostgreSQL']
        const learning      = 'nestjs'
        const ide           = ['Visual Studio Code', 'Notepad']

        const preferredLanguage = languages[1];

        return languages, learning, ide, preferredLanguage
    }
}

export default Nasvan
