# Codes-Practice

#Armstrong Number(3 digit)

string armstrongNumber(int n){
        // code here
        int on=n;
        int cubeSum=0,digit=0;
        while(n>0)
        {
            digit=n%10;
            cubeSum+=pow(digit,3);
            n=n/10;
        }
        
        if(cubeSum==on)
        {
            return "Yes";
        }
        else
        {
            return "No";
        }
    }
