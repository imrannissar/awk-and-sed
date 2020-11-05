# SED and AWK

_commands_

- awk '/google.com/ {print}' domains.txt **Print the line which matches the given pattern**
- awk '{print "https://" $0;}' test.txt > test1.txt **Adds https infornt of each line**
- awk '{print $1}' **Removes everything after space**
- sed 's/https\?:\/\///' **Remove https**
- sed 's/http\?:\/\///' **Remove http**
- sed '/bar/d' **Remove whole line if bar is present**
- sed -i 's|http://|https://|g'  test.txt **Replace http to https in a give file**
- sed -e '/000/d' -e '/301/d' -e '/302/d' -e '/000/d' -e '/404/d' -e '/ **Remove multiple patterns**
- sed -e 's/olddata/newdata/g' fileold > filenew **Replace all matching occurance**
- sed '4 s/test/test1/' **Replace string on a specific line number**
- sed '1,3 s/unix/linux/' **Replace strings on a range of lines**
- sed '3,6d' **To delete line from range 3-6**
 
 
