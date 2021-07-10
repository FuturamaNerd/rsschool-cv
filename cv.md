# David Mdzinarishvili
## contact info
**email**

DMsaqartvelo@gmail.com

**phone number**

599 495 505
## about me
I was born in Tbilisi but, grew up in a small American city Omaha, Nebraska. I moved back here when I was 15 and attended an IB high school. I was enthraled with web
development in my early teens and made the choice to study cmputer engineering in college. Having learned C and C++ as well as the basic concepts of coding I am now
studying python and planning and taking a web development course both of which I am eager to learn.
## skills
* fluent in C and C++
* novice in Python
* some knowledge in assembly languages
## code sample
**random number generator**

typedef unsigned int LinearFeedbackShiftRegister;
LinearFeedbackShiftRegister LFSR32Bit, LFSR31Bit;

int ShiftLFSR(LinearFeedbackShiftRegister *LFSR, LinearFeedbackShiftRegister Polynomial){
    int Feedback;
    Feedback = *LFSR & 1;
    *LFSR >>= 1;
    if (Feedback == 1){
        *LFSR ^= Polynomial;
        return *LFSR;
    }
    else{
        return 1;
    }
}
## experience

* assisted in the setting up of a book fair
* coded several encryptors for a university project in C
* coded prototypes for restaurant software, ecological simulator
* successfully implemented several data structures such as self-balancing and non-self-balancing search trees
## education

**high school**
* British-Georgian School
* New School international

**university**

* currently enrolled in San Diego State University
* currently taking an introductory course in web development


## language

* fluent in english
* intermediate knowledge of georgian


void SeedNumbers(){
    LFSR32Bit = 0xF0F0F;
    LFSR31Bit = 0x82340145;
}

int Random(){
    ShiftLFSR(&LFSR32Bit,POLYNOMIAL_32_BIT);
    return (ShiftLFSR(&LFSR32Bit,POLYNOMIAL_32_BIT)^ ShiftLFSR(&LFSR31Bit,POLYNOMIAL_31_BIT)) &0xffff;
}

int main()
{
   int RandomNumber;
   SeedNumbers();
   RandomNumber = Random();
   printf("%d", RandomNumber);
    return 0;
}

## experience

* assisted in the setting up of a book fair
* coded several encryptors for a university project in C
* coded prototypes for restaurant software, ecological simulator
* successfully implemented several data structures such as self-balancing and non-self-balancing search trees
## education

**high school**
* British-Georgian School
* New School international

**university**

* currently enrolled in San Diego State University
* currently taking an introductory course in web development

