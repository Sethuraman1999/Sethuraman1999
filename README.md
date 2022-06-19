 import java.util.Arraylist;
import com.google.api.translate.Language;
import com.google.api.translate.Translator;
public class Translation{
  public static viod main(String args[]){
    Translator translator=new Translator();
    System.out.println("saying abide in french:");
    System.out.println("translator.translate("abide",Language.ENGLISH, Language.FRENCH));
    System.out.println();
  }
}
