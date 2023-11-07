# Truncate-Sentence-using-Java-Leetcode
    class Solution {
        public String truncateSentence(String s, int k) {
            String[] result = s.split(" ");
            String re ="";
            for(int i =0;i<k;i++){
                if(i<result.length){
                    re=re+result[i]+" ";
                }
               
            }
            return re.trim();
        }
    }
