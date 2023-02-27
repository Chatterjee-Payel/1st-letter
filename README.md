# 1st-letter
class Solution{
public:	
	
	string firstAlphabet(string S)
	{
	    // Your code goes here
	    string ans="";
	   ans+=S[0];
	   for(int i=0;i<S.size();i++){
	       if(S[i]==' '){
	           ans+=S[i+1];
	       }
	   }
	   return ans;
	}
};
