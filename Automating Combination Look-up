#By: ANJALI THATTE
#Date: July 19
#Purpose: Outline list of input combinations for BT840 interface


print "Combinatins of Input for PB840 New Patient\n"

ventType=["invasive", "niv"]
mode=["a/c","simv", "spont", "bilevel"]
mandType=["pc", "vc", "vc+"]
triggerType=["vtrig", "ptrig"]

directory=[]
action=int(input("1 for printing all combinations; 2 for printing one combination"))


count=1
for i in range (len(ventType)):
    for j in range (len(mode)):
        for k in range (len(mandType)):
            for l in range (len(triggerType)):
                if (i==0):
                    newCase=' {: <15}'.format(ventType[i])+'{: <15}'.format(mode[j])+'{: <15}'.format(mandType[k])+'{: <15}'.format(triggerType[l])
                    directory.append(newCase)
                    
                    if (action==1):
                        print str(count)+"."+newCase 
                        
                    count+=1
                    
                    
                elif ((j!=3)and(k!=2)and(l!=1)):
                    
                    newCase=' {: <15}'.format(ventType[i])+'{: <15}'.format(mode[j])+'{: <15}'.format(mandType[k])+'{: <15}'.format(triggerType[l])
                    directory.append(newCase)
                    if (action==1):
                        print str(count)+"."+newCase
                    
                    count+=1


if(action==2):
    case=int(input("Case: "))
    print directory[case-1]
