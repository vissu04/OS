echo enter a number
read a
i=2
fact=1
if [ $a -ge 2 ]
then
while [ $i -le $a ]
do
fact=`expr $fact \* $i`
i=`expr $i + 1`
done
fi
echo factorial of $a=$fact
