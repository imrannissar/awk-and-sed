# awk-and-sed
commands


- awk '{print "https://" $0;}' test.txt > test1.txt **Adds https infornt of each line**
- awk '{print $1}' **removes everything after space**
- sed 's/https\?:\/\///' **Remove https
- sed 's/http\?:\/\///' **Remove http*
- sed '/bar/d' **Remove whole line if bar is present**
- sed -i 's|http://|https://|g'  test.txt **Replace http to https in a give file**
- sed -e '/000/d' -e '/301/d' -e '/302/d' -e '/000/d' -e '/404/d' -e '/ remove multiple patterns
- sed -e 's/olddata/newdata/g' fileold > filenew **Replace all matching occurance**
 
