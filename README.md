# -#变量
#phone_number = "+91123456789"
#print(phone_number)

#字符串长度及类型
#B="No me gusta trabajar"
#print(B[4])
#print(tepy(B))


#Input
#Nomina=float(input("Deja tu nomina:"))
#Entrada=float(input("Deja la entrada:"))
#Precio_del_piso=float(input("Precio del Piso:"))
#Deuda_anual=float((Precio_del_piso-Entrada)/Nomina/0.3)
#print("年贷款："+ str(Deuda_anual))


#条件式
#Nomina=float(input("本月入账："))
#Gasto=float(input("本月消费："))
#Ahorra= float((Nomina-Gasto)/Nomina)

#if Ahorra <=0.4:
 #print("别买衣服了！")
#else:
#print("好耶，又可以买衣服了！")


#嵌套条件
#weight=int(input("请输入今天摄入的卡路里："))
#execise=int(input("请输入今天运动消耗的卡路里："))
#calorie=weight-exercise
#print("今天摄入卡路里"+str(calorie))
# if calorie>1500:
#     print("住嘴吧")
# elif calorie<1500:
#     print("好吧，可以再吃一点点。")
#
# temperadura=int((input("气温：")))
# energy=int(input("能量"))
# happy=ture
#
# if temperadura< 30 and energy>8 and not happy:
#     print("去打网球吧")

# #方法&可变和不可变
# business_trip=[]
# business_trip.append("眼罩")
# business_trip.append("耳塞")
# business_trip.append("行李箱")
# business_trip.append("书")
# print(business_trip)
# business_trip.remove("耳塞")
# print(business_trip)
# print(len(business_trip))
# print(business_trip[2])

#Dictionary key:value
# contact={"xiaoming":"123","Bobo":"345"}
# contact["Lala"]=567
# print(contact)
# print("Bobo" in contact)
# del contact["Bobo"]
#
# query= input("请输入要查询的人员：")
# if query in contact:
#     print("您查询的人员"+ query+"号码是"+ str(contact[query]))
# else:
#     print("您查询的人员不在列表中")

#Range
# for i in range(1,10,3):
#     print(i)

# for，while
# print("计算机：")
# total=0
# count=0
# num=input("请输入需要计算平均值的数字,请输入s结束程序：")
# while num != "s":
#     num=float(num)
#     total +=num
#     count+=1
#     num = input("请输入需要计算平均值的数字,请输入s结束程序：")
# if count==0:
#     result=0
# else:
#     result=total/count
# print("平均值为：" + str(result))

#定制信息,format,f-字符串
# contacts=["Ana", "Louis","Bob"]
# date= "01.08"
#
# for name in contacts:
#     print(f""" {name}, Thank you for contacting me!
#           I will reply you on {date}""")
