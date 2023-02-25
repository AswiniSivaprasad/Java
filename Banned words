import java.util.*;

public class banned {

    public static String findMostFrequentWord(String paragraph, String[] banned) {
        String[] words = paragraph.toLowerCase().split("[^a-zA-Z]+");

        Map<String, Integer> wordFreq = new HashMap<>();


        for (String word : words) {
            if (!Arrays.asList(banned).contains(word)) {
                wordFreq.put(word, wordFreq.getOrDefault(word, 0) + 1);
            }
        }

        String mostFrequentWord = "";
        int maxFreq = 0;
        for (Map.Entry<String, Integer> entry : wordFreq.entrySet()) {
            if (entry.getValue() > maxFreq) {
                mostFrequentWord = entry.getKey();
                maxFreq = entry.getValue();
            }
        }

        return mostFrequentWord;
    }

    public static void main(String[] args) {
        String paragraph = "Ram hit a ball, the hit ball flew far after it was hit";
        String[] banned = {"hit"};
        String mostFrequentWord = findMostFrequentWord(paragraph, banned);
        System.out.println(mostFrequentWord);
    }
}
