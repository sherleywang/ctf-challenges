# Unique Message
Prompt: A super secure message has been sent by the government, but they forgot to tell everyone how to decode it. You overheard the Secret Service talking about a unique message within lines of junk text...
Flag is in the format utflag{_______}

Solution:
1. Use the "cat" command to print out the message file
2. Use the "sort" command to sort everything in alphabetical order
3. Use the "uniq -u" command to only extract the line that is unique (the message)
4. Combine steps 1-3 by piping the commands: cat message.txt | sort | uniq -u
5. Decode the Base 64 encoded message to get the flag

Answer:
utflag{5tay_h0m3_2020}
