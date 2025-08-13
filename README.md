public class consecutive_number
{
    public String consecutive_number(int[] arreglo){
        String res="";
        int cConsecutivos=0;
        if(arreglo.length>=2){
            for(int i =0; i< arreglo.length-1; i++){
                if((arreglo[i+1])-(arreglo[i])==1){
                    cConsecutivos++;
                }
            }
        }
        
        if(cConsecutivos==arreglo.length-1){
            res= "null";
        }
        
        return res;
    }
}
