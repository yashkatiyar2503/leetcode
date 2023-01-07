class Solution {
    public boolean isSameAfterReversals(int num) {
        int n=rev(num);
        if(num==rev(n))
            return true;
        else
            return false;
    }
    int rev(int x)
    {
        int r=0;
        while(x!=0)
        {
            int d=x%10;
            r=r*10+d;
            x=x/10;
        }
        return r;
    }
}
