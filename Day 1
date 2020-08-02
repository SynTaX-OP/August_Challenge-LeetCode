class Solution {
public:
    bool detectCapitalUse(string word) {
        bool b=0;
        int c=0,s=0;
        for(int i=0;i<word.size();i++)
        {
          if(word[i]>='A' && word[i]<='Z')
          {
              if(i==0){b=1;}
              c++;
          }
            else{s++;}
        }
       bool ans= (c==word.size() ||s==word.size() ||(s==word.size()-1 && b));
         return ans;         
    }
};
