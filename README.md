# WordCounter
A program that gathers both a word and sentence from a user, then checks how frequently the word appears in the sentence.
| Behavior | Input | Output |
| ------------- |:-------------:| -----:|
| makes inputted sentence lowercase string | Hello World | "hello world" |
| makes inputted word lowercase string | Hello | "hello" |
| split lowercase string sentence into array of strings | "hello world" | {"hello", "world"} |
| compare string array to inputted word for pairs | world == hello | false |
| add one for each pair | (hello == hello) | pairs +=1 |
