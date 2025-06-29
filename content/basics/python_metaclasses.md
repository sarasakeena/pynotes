---
title: Python Metaclasses
date: 2025-06-30
author: Your Name
cell_count: 500
score: 500
---

```
class Meta1(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 1
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta1(metaclass=Meta1):
    def show_meta_id(self):
        return self.meta_id

obj1 = ClassWithMeta1()
obj1.show_meta_id()
```


```
class Meta2(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 2
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta2(metaclass=Meta2):
    def show_meta_id(self):
        return self.meta_id

obj2 = ClassWithMeta2()
obj2.show_meta_id()
```


```
class Meta3(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 3
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta3(metaclass=Meta3):
    def show_meta_id(self):
        return self.meta_id

obj3 = ClassWithMeta3()
obj3.show_meta_id()
```


```
class Meta4(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 4
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta4(metaclass=Meta4):
    def show_meta_id(self):
        return self.meta_id

obj4 = ClassWithMeta4()
obj4.show_meta_id()
```


```
class Meta5(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 5
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta5(metaclass=Meta5):
    def show_meta_id(self):
        return self.meta_id

obj5 = ClassWithMeta5()
obj5.show_meta_id()
```


```
class Meta6(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 6
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta6(metaclass=Meta6):
    def show_meta_id(self):
        return self.meta_id

obj6 = ClassWithMeta6()
obj6.show_meta_id()
```


```
class Meta7(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 7
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta7(metaclass=Meta7):
    def show_meta_id(self):
        return self.meta_id

obj7 = ClassWithMeta7()
obj7.show_meta_id()
```


```
class Meta8(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 8
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta8(metaclass=Meta8):
    def show_meta_id(self):
        return self.meta_id

obj8 = ClassWithMeta8()
obj8.show_meta_id()
```


```
class Meta9(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 9
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta9(metaclass=Meta9):
    def show_meta_id(self):
        return self.meta_id

obj9 = ClassWithMeta9()
obj9.show_meta_id()
```


```
class Meta10(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 10
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta10(metaclass=Meta10):
    def show_meta_id(self):
        return self.meta_id

obj10 = ClassWithMeta10()
obj10.show_meta_id()
```


```
class Meta11(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 11
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta11(metaclass=Meta11):
    def show_meta_id(self):
        return self.meta_id

obj11 = ClassWithMeta11()
obj11.show_meta_id()
```


```
class Meta12(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 12
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta12(metaclass=Meta12):
    def show_meta_id(self):
        return self.meta_id

obj12 = ClassWithMeta12()
obj12.show_meta_id()
```


```
class Meta13(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 13
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta13(metaclass=Meta13):
    def show_meta_id(self):
        return self.meta_id

obj13 = ClassWithMeta13()
obj13.show_meta_id()
```


```
class Meta14(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 14
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta14(metaclass=Meta14):
    def show_meta_id(self):
        return self.meta_id

obj14 = ClassWithMeta14()
obj14.show_meta_id()
```


```
class Meta15(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 15
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta15(metaclass=Meta15):
    def show_meta_id(self):
        return self.meta_id

obj15 = ClassWithMeta15()
obj15.show_meta_id()
```


```
class Meta16(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 16
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta16(metaclass=Meta16):
    def show_meta_id(self):
        return self.meta_id

obj16 = ClassWithMeta16()
obj16.show_meta_id()
```


```
class Meta17(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 17
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta17(metaclass=Meta17):
    def show_meta_id(self):
        return self.meta_id

obj17 = ClassWithMeta17()
obj17.show_meta_id()
```


```
class Meta18(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 18
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta18(metaclass=Meta18):
    def show_meta_id(self):
        return self.meta_id

obj18 = ClassWithMeta18()
obj18.show_meta_id()
```


```
class Meta19(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 19
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta19(metaclass=Meta19):
    def show_meta_id(self):
        return self.meta_id

obj19 = ClassWithMeta19()
obj19.show_meta_id()
```


```
class Meta20(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 20
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta20(metaclass=Meta20):
    def show_meta_id(self):
        return self.meta_id

obj20 = ClassWithMeta20()
obj20.show_meta_id()
```


```
class Meta21(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 21
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta21(metaclass=Meta21):
    def show_meta_id(self):
        return self.meta_id

obj21 = ClassWithMeta21()
obj21.show_meta_id()
```


```
class Meta22(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 22
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta22(metaclass=Meta22):
    def show_meta_id(self):
        return self.meta_id

obj22 = ClassWithMeta22()
obj22.show_meta_id()
```


```
class Meta23(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 23
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta23(metaclass=Meta23):
    def show_meta_id(self):
        return self.meta_id

obj23 = ClassWithMeta23()
obj23.show_meta_id()
```


```
class Meta24(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 24
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta24(metaclass=Meta24):
    def show_meta_id(self):
        return self.meta_id

obj24 = ClassWithMeta24()
obj24.show_meta_id()
```


```
class Meta25(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 25
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta25(metaclass=Meta25):
    def show_meta_id(self):
        return self.meta_id

obj25 = ClassWithMeta25()
obj25.show_meta_id()
```


```
class Meta26(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 26
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta26(metaclass=Meta26):
    def show_meta_id(self):
        return self.meta_id

obj26 = ClassWithMeta26()
obj26.show_meta_id()
```


```
class Meta27(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 27
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta27(metaclass=Meta27):
    def show_meta_id(self):
        return self.meta_id

obj27 = ClassWithMeta27()
obj27.show_meta_id()
```


```
class Meta28(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 28
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta28(metaclass=Meta28):
    def show_meta_id(self):
        return self.meta_id

obj28 = ClassWithMeta28()
obj28.show_meta_id()
```


```
class Meta29(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 29
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta29(metaclass=Meta29):
    def show_meta_id(self):
        return self.meta_id

obj29 = ClassWithMeta29()
obj29.show_meta_id()
```


```
class Meta30(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 30
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta30(metaclass=Meta30):
    def show_meta_id(self):
        return self.meta_id

obj30 = ClassWithMeta30()
obj30.show_meta_id()
```


```
class Meta31(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 31
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta31(metaclass=Meta31):
    def show_meta_id(self):
        return self.meta_id

obj31 = ClassWithMeta31()
obj31.show_meta_id()
```


```
class Meta32(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 32
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta32(metaclass=Meta32):
    def show_meta_id(self):
        return self.meta_id

obj32 = ClassWithMeta32()
obj32.show_meta_id()
```


```
class Meta33(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 33
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta33(metaclass=Meta33):
    def show_meta_id(self):
        return self.meta_id

obj33 = ClassWithMeta33()
obj33.show_meta_id()
```


```
class Meta34(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 34
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta34(metaclass=Meta34):
    def show_meta_id(self):
        return self.meta_id

obj34 = ClassWithMeta34()
obj34.show_meta_id()
```


```
class Meta35(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 35
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta35(metaclass=Meta35):
    def show_meta_id(self):
        return self.meta_id

obj35 = ClassWithMeta35()
obj35.show_meta_id()
```


```
class Meta36(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 36
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta36(metaclass=Meta36):
    def show_meta_id(self):
        return self.meta_id

obj36 = ClassWithMeta36()
obj36.show_meta_id()
```


```
class Meta37(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 37
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta37(metaclass=Meta37):
    def show_meta_id(self):
        return self.meta_id

obj37 = ClassWithMeta37()
obj37.show_meta_id()
```


```
class Meta38(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 38
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta38(metaclass=Meta38):
    def show_meta_id(self):
        return self.meta_id

obj38 = ClassWithMeta38()
obj38.show_meta_id()
```


```
class Meta39(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 39
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta39(metaclass=Meta39):
    def show_meta_id(self):
        return self.meta_id

obj39 = ClassWithMeta39()
obj39.show_meta_id()
```


```
class Meta40(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 40
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta40(metaclass=Meta40):
    def show_meta_id(self):
        return self.meta_id

obj40 = ClassWithMeta40()
obj40.show_meta_id()
```


```
class Meta41(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 41
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta41(metaclass=Meta41):
    def show_meta_id(self):
        return self.meta_id

obj41 = ClassWithMeta41()
obj41.show_meta_id()
```


```
class Meta42(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 42
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta42(metaclass=Meta42):
    def show_meta_id(self):
        return self.meta_id

obj42 = ClassWithMeta42()
obj42.show_meta_id()
```


```
class Meta43(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 43
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta43(metaclass=Meta43):
    def show_meta_id(self):
        return self.meta_id

obj43 = ClassWithMeta43()
obj43.show_meta_id()
```


```
class Meta44(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 44
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta44(metaclass=Meta44):
    def show_meta_id(self):
        return self.meta_id

obj44 = ClassWithMeta44()
obj44.show_meta_id()
```


```
class Meta45(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 45
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta45(metaclass=Meta45):
    def show_meta_id(self):
        return self.meta_id

obj45 = ClassWithMeta45()
obj45.show_meta_id()
```


```
class Meta46(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 46
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta46(metaclass=Meta46):
    def show_meta_id(self):
        return self.meta_id

obj46 = ClassWithMeta46()
obj46.show_meta_id()
```


```
class Meta47(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 47
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta47(metaclass=Meta47):
    def show_meta_id(self):
        return self.meta_id

obj47 = ClassWithMeta47()
obj47.show_meta_id()
```


```
class Meta48(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 48
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta48(metaclass=Meta48):
    def show_meta_id(self):
        return self.meta_id

obj48 = ClassWithMeta48()
obj48.show_meta_id()
```


```
class Meta49(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 49
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta49(metaclass=Meta49):
    def show_meta_id(self):
        return self.meta_id

obj49 = ClassWithMeta49()
obj49.show_meta_id()
```


```
class Meta50(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 50
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta50(metaclass=Meta50):
    def show_meta_id(self):
        return self.meta_id

obj50 = ClassWithMeta50()
obj50.show_meta_id()
```


```
class Meta51(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 51
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta51(metaclass=Meta51):
    def show_meta_id(self):
        return self.meta_id

obj51 = ClassWithMeta51()
obj51.show_meta_id()
```


```
class Meta52(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 52
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta52(metaclass=Meta52):
    def show_meta_id(self):
        return self.meta_id

obj52 = ClassWithMeta52()
obj52.show_meta_id()
```


```
class Meta53(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 53
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta53(metaclass=Meta53):
    def show_meta_id(self):
        return self.meta_id

obj53 = ClassWithMeta53()
obj53.show_meta_id()
```


```
class Meta54(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 54
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta54(metaclass=Meta54):
    def show_meta_id(self):
        return self.meta_id

obj54 = ClassWithMeta54()
obj54.show_meta_id()
```


```
class Meta55(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 55
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta55(metaclass=Meta55):
    def show_meta_id(self):
        return self.meta_id

obj55 = ClassWithMeta55()
obj55.show_meta_id()
```


```
class Meta56(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 56
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta56(metaclass=Meta56):
    def show_meta_id(self):
        return self.meta_id

obj56 = ClassWithMeta56()
obj56.show_meta_id()
```


```
class Meta57(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 57
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta57(metaclass=Meta57):
    def show_meta_id(self):
        return self.meta_id

obj57 = ClassWithMeta57()
obj57.show_meta_id()
```


```
class Meta58(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 58
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta58(metaclass=Meta58):
    def show_meta_id(self):
        return self.meta_id

obj58 = ClassWithMeta58()
obj58.show_meta_id()
```


```
class Meta59(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 59
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta59(metaclass=Meta59):
    def show_meta_id(self):
        return self.meta_id

obj59 = ClassWithMeta59()
obj59.show_meta_id()
```


```
class Meta60(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 60
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta60(metaclass=Meta60):
    def show_meta_id(self):
        return self.meta_id

obj60 = ClassWithMeta60()
obj60.show_meta_id()
```


```
class Meta61(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 61
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta61(metaclass=Meta61):
    def show_meta_id(self):
        return self.meta_id

obj61 = ClassWithMeta61()
obj61.show_meta_id()
```


```
class Meta62(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 62
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta62(metaclass=Meta62):
    def show_meta_id(self):
        return self.meta_id

obj62 = ClassWithMeta62()
obj62.show_meta_id()
```


```
class Meta63(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 63
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta63(metaclass=Meta63):
    def show_meta_id(self):
        return self.meta_id

obj63 = ClassWithMeta63()
obj63.show_meta_id()
```


```
class Meta64(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 64
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta64(metaclass=Meta64):
    def show_meta_id(self):
        return self.meta_id

obj64 = ClassWithMeta64()
obj64.show_meta_id()
```


```
class Meta65(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 65
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta65(metaclass=Meta65):
    def show_meta_id(self):
        return self.meta_id

obj65 = ClassWithMeta65()
obj65.show_meta_id()
```


```
class Meta66(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 66
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta66(metaclass=Meta66):
    def show_meta_id(self):
        return self.meta_id

obj66 = ClassWithMeta66()
obj66.show_meta_id()
```


```
class Meta67(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 67
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta67(metaclass=Meta67):
    def show_meta_id(self):
        return self.meta_id

obj67 = ClassWithMeta67()
obj67.show_meta_id()
```


```
class Meta68(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 68
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta68(metaclass=Meta68):
    def show_meta_id(self):
        return self.meta_id

obj68 = ClassWithMeta68()
obj68.show_meta_id()
```


```
class Meta69(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 69
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta69(metaclass=Meta69):
    def show_meta_id(self):
        return self.meta_id

obj69 = ClassWithMeta69()
obj69.show_meta_id()
```


```
class Meta70(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 70
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta70(metaclass=Meta70):
    def show_meta_id(self):
        return self.meta_id

obj70 = ClassWithMeta70()
obj70.show_meta_id()
```


```
class Meta71(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 71
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta71(metaclass=Meta71):
    def show_meta_id(self):
        return self.meta_id

obj71 = ClassWithMeta71()
obj71.show_meta_id()
```


```
class Meta72(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 72
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta72(metaclass=Meta72):
    def show_meta_id(self):
        return self.meta_id

obj72 = ClassWithMeta72()
obj72.show_meta_id()
```


```
class Meta73(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 73
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta73(metaclass=Meta73):
    def show_meta_id(self):
        return self.meta_id

obj73 = ClassWithMeta73()
obj73.show_meta_id()
```


```
class Meta74(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 74
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta74(metaclass=Meta74):
    def show_meta_id(self):
        return self.meta_id

obj74 = ClassWithMeta74()
obj74.show_meta_id()
```


```
class Meta75(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 75
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta75(metaclass=Meta75):
    def show_meta_id(self):
        return self.meta_id

obj75 = ClassWithMeta75()
obj75.show_meta_id()
```


```
class Meta76(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 76
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta76(metaclass=Meta76):
    def show_meta_id(self):
        return self.meta_id

obj76 = ClassWithMeta76()
obj76.show_meta_id()
```


```
class Meta77(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 77
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta77(metaclass=Meta77):
    def show_meta_id(self):
        return self.meta_id

obj77 = ClassWithMeta77()
obj77.show_meta_id()
```


```
class Meta78(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 78
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta78(metaclass=Meta78):
    def show_meta_id(self):
        return self.meta_id

obj78 = ClassWithMeta78()
obj78.show_meta_id()
```


```
class Meta79(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 79
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta79(metaclass=Meta79):
    def show_meta_id(self):
        return self.meta_id

obj79 = ClassWithMeta79()
obj79.show_meta_id()
```


```
class Meta80(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 80
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta80(metaclass=Meta80):
    def show_meta_id(self):
        return self.meta_id

obj80 = ClassWithMeta80()
obj80.show_meta_id()
```


```
class Meta81(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 81
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta81(metaclass=Meta81):
    def show_meta_id(self):
        return self.meta_id

obj81 = ClassWithMeta81()
obj81.show_meta_id()
```


```
class Meta82(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 82
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta82(metaclass=Meta82):
    def show_meta_id(self):
        return self.meta_id

obj82 = ClassWithMeta82()
obj82.show_meta_id()
```


```
class Meta83(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 83
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta83(metaclass=Meta83):
    def show_meta_id(self):
        return self.meta_id

obj83 = ClassWithMeta83()
obj83.show_meta_id()
```


```
class Meta84(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 84
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta84(metaclass=Meta84):
    def show_meta_id(self):
        return self.meta_id

obj84 = ClassWithMeta84()
obj84.show_meta_id()
```


```
class Meta85(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 85
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta85(metaclass=Meta85):
    def show_meta_id(self):
        return self.meta_id

obj85 = ClassWithMeta85()
obj85.show_meta_id()
```


```
class Meta86(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 86
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta86(metaclass=Meta86):
    def show_meta_id(self):
        return self.meta_id

obj86 = ClassWithMeta86()
obj86.show_meta_id()
```


```
class Meta87(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 87
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta87(metaclass=Meta87):
    def show_meta_id(self):
        return self.meta_id

obj87 = ClassWithMeta87()
obj87.show_meta_id()
```


```
class Meta88(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 88
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta88(metaclass=Meta88):
    def show_meta_id(self):
        return self.meta_id

obj88 = ClassWithMeta88()
obj88.show_meta_id()
```


```
class Meta89(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 89
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta89(metaclass=Meta89):
    def show_meta_id(self):
        return self.meta_id

obj89 = ClassWithMeta89()
obj89.show_meta_id()
```


```
class Meta90(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 90
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta90(metaclass=Meta90):
    def show_meta_id(self):
        return self.meta_id

obj90 = ClassWithMeta90()
obj90.show_meta_id()
```


```
class Meta91(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 91
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta91(metaclass=Meta91):
    def show_meta_id(self):
        return self.meta_id

obj91 = ClassWithMeta91()
obj91.show_meta_id()
```


```
class Meta92(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 92
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta92(metaclass=Meta92):
    def show_meta_id(self):
        return self.meta_id

obj92 = ClassWithMeta92()
obj92.show_meta_id()
```


```
class Meta93(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 93
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta93(metaclass=Meta93):
    def show_meta_id(self):
        return self.meta_id

obj93 = ClassWithMeta93()
obj93.show_meta_id()
```


```
class Meta94(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 94
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta94(metaclass=Meta94):
    def show_meta_id(self):
        return self.meta_id

obj94 = ClassWithMeta94()
obj94.show_meta_id()
```


```
class Meta95(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 95
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta95(metaclass=Meta95):
    def show_meta_id(self):
        return self.meta_id

obj95 = ClassWithMeta95()
obj95.show_meta_id()
```


```
class Meta96(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 96
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta96(metaclass=Meta96):
    def show_meta_id(self):
        return self.meta_id

obj96 = ClassWithMeta96()
obj96.show_meta_id()
```


```
class Meta97(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 97
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta97(metaclass=Meta97):
    def show_meta_id(self):
        return self.meta_id

obj97 = ClassWithMeta97()
obj97.show_meta_id()
```


```
class Meta98(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 98
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta98(metaclass=Meta98):
    def show_meta_id(self):
        return self.meta_id

obj98 = ClassWithMeta98()
obj98.show_meta_id()
```


```
class Meta99(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 99
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta99(metaclass=Meta99):
    def show_meta_id(self):
        return self.meta_id

obj99 = ClassWithMeta99()
obj99.show_meta_id()
```


```
class Meta100(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 100
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta100(metaclass=Meta100):
    def show_meta_id(self):
        return self.meta_id

obj100 = ClassWithMeta100()
obj100.show_meta_id()
```


```
class Meta101(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 101
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta101(metaclass=Meta101):
    def show_meta_id(self):
        return self.meta_id

obj101 = ClassWithMeta101()
obj101.show_meta_id()
```


```
class Meta102(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 102
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta102(metaclass=Meta102):
    def show_meta_id(self):
        return self.meta_id

obj102 = ClassWithMeta102()
obj102.show_meta_id()
```


```
class Meta103(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 103
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta103(metaclass=Meta103):
    def show_meta_id(self):
        return self.meta_id

obj103 = ClassWithMeta103()
obj103.show_meta_id()
```


```
class Meta104(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 104
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta104(metaclass=Meta104):
    def show_meta_id(self):
        return self.meta_id

obj104 = ClassWithMeta104()
obj104.show_meta_id()
```


```
class Meta105(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 105
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta105(metaclass=Meta105):
    def show_meta_id(self):
        return self.meta_id

obj105 = ClassWithMeta105()
obj105.show_meta_id()
```


```
class Meta106(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 106
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta106(metaclass=Meta106):
    def show_meta_id(self):
        return self.meta_id

obj106 = ClassWithMeta106()
obj106.show_meta_id()
```


```
class Meta107(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 107
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta107(metaclass=Meta107):
    def show_meta_id(self):
        return self.meta_id

obj107 = ClassWithMeta107()
obj107.show_meta_id()
```


```
class Meta108(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 108
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta108(metaclass=Meta108):
    def show_meta_id(self):
        return self.meta_id

obj108 = ClassWithMeta108()
obj108.show_meta_id()
```


```
class Meta109(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 109
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta109(metaclass=Meta109):
    def show_meta_id(self):
        return self.meta_id

obj109 = ClassWithMeta109()
obj109.show_meta_id()
```


```
class Meta110(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 110
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta110(metaclass=Meta110):
    def show_meta_id(self):
        return self.meta_id

obj110 = ClassWithMeta110()
obj110.show_meta_id()
```


```
class Meta111(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 111
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta111(metaclass=Meta111):
    def show_meta_id(self):
        return self.meta_id

obj111 = ClassWithMeta111()
obj111.show_meta_id()
```


```
class Meta112(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 112
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta112(metaclass=Meta112):
    def show_meta_id(self):
        return self.meta_id

obj112 = ClassWithMeta112()
obj112.show_meta_id()
```


```
class Meta113(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 113
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta113(metaclass=Meta113):
    def show_meta_id(self):
        return self.meta_id

obj113 = ClassWithMeta113()
obj113.show_meta_id()
```


```
class Meta114(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 114
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta114(metaclass=Meta114):
    def show_meta_id(self):
        return self.meta_id

obj114 = ClassWithMeta114()
obj114.show_meta_id()
```


```
class Meta115(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 115
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta115(metaclass=Meta115):
    def show_meta_id(self):
        return self.meta_id

obj115 = ClassWithMeta115()
obj115.show_meta_id()
```


```
class Meta116(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 116
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta116(metaclass=Meta116):
    def show_meta_id(self):
        return self.meta_id

obj116 = ClassWithMeta116()
obj116.show_meta_id()
```


```
class Meta117(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 117
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta117(metaclass=Meta117):
    def show_meta_id(self):
        return self.meta_id

obj117 = ClassWithMeta117()
obj117.show_meta_id()
```


```
class Meta118(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 118
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta118(metaclass=Meta118):
    def show_meta_id(self):
        return self.meta_id

obj118 = ClassWithMeta118()
obj118.show_meta_id()
```


```
class Meta119(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 119
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta119(metaclass=Meta119):
    def show_meta_id(self):
        return self.meta_id

obj119 = ClassWithMeta119()
obj119.show_meta_id()
```


```
class Meta120(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 120
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta120(metaclass=Meta120):
    def show_meta_id(self):
        return self.meta_id

obj120 = ClassWithMeta120()
obj120.show_meta_id()
```


```
class Meta121(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 121
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta121(metaclass=Meta121):
    def show_meta_id(self):
        return self.meta_id

obj121 = ClassWithMeta121()
obj121.show_meta_id()
```


```
class Meta122(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 122
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta122(metaclass=Meta122):
    def show_meta_id(self):
        return self.meta_id

obj122 = ClassWithMeta122()
obj122.show_meta_id()
```


```
class Meta123(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 123
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta123(metaclass=Meta123):
    def show_meta_id(self):
        return self.meta_id

obj123 = ClassWithMeta123()
obj123.show_meta_id()
```


```
class Meta124(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 124
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta124(metaclass=Meta124):
    def show_meta_id(self):
        return self.meta_id

obj124 = ClassWithMeta124()
obj124.show_meta_id()
```


```
class Meta125(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 125
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta125(metaclass=Meta125):
    def show_meta_id(self):
        return self.meta_id

obj125 = ClassWithMeta125()
obj125.show_meta_id()
```


```
class Meta126(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 126
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta126(metaclass=Meta126):
    def show_meta_id(self):
        return self.meta_id

obj126 = ClassWithMeta126()
obj126.show_meta_id()
```


```
class Meta127(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 127
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta127(metaclass=Meta127):
    def show_meta_id(self):
        return self.meta_id

obj127 = ClassWithMeta127()
obj127.show_meta_id()
```


```
class Meta128(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 128
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta128(metaclass=Meta128):
    def show_meta_id(self):
        return self.meta_id

obj128 = ClassWithMeta128()
obj128.show_meta_id()
```


```
class Meta129(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 129
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta129(metaclass=Meta129):
    def show_meta_id(self):
        return self.meta_id

obj129 = ClassWithMeta129()
obj129.show_meta_id()
```


```
class Meta130(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 130
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta130(metaclass=Meta130):
    def show_meta_id(self):
        return self.meta_id

obj130 = ClassWithMeta130()
obj130.show_meta_id()
```


```
class Meta131(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 131
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta131(metaclass=Meta131):
    def show_meta_id(self):
        return self.meta_id

obj131 = ClassWithMeta131()
obj131.show_meta_id()
```


```
class Meta132(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 132
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta132(metaclass=Meta132):
    def show_meta_id(self):
        return self.meta_id

obj132 = ClassWithMeta132()
obj132.show_meta_id()
```


```
class Meta133(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 133
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta133(metaclass=Meta133):
    def show_meta_id(self):
        return self.meta_id

obj133 = ClassWithMeta133()
obj133.show_meta_id()
```


```
class Meta134(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 134
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta134(metaclass=Meta134):
    def show_meta_id(self):
        return self.meta_id

obj134 = ClassWithMeta134()
obj134.show_meta_id()
```


```
class Meta135(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 135
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta135(metaclass=Meta135):
    def show_meta_id(self):
        return self.meta_id

obj135 = ClassWithMeta135()
obj135.show_meta_id()
```


```
class Meta136(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 136
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta136(metaclass=Meta136):
    def show_meta_id(self):
        return self.meta_id

obj136 = ClassWithMeta136()
obj136.show_meta_id()
```


```
class Meta137(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 137
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta137(metaclass=Meta137):
    def show_meta_id(self):
        return self.meta_id

obj137 = ClassWithMeta137()
obj137.show_meta_id()
```


```
class Meta138(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 138
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta138(metaclass=Meta138):
    def show_meta_id(self):
        return self.meta_id

obj138 = ClassWithMeta138()
obj138.show_meta_id()
```


```
class Meta139(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 139
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta139(metaclass=Meta139):
    def show_meta_id(self):
        return self.meta_id

obj139 = ClassWithMeta139()
obj139.show_meta_id()
```


```
class Meta140(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 140
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta140(metaclass=Meta140):
    def show_meta_id(self):
        return self.meta_id

obj140 = ClassWithMeta140()
obj140.show_meta_id()
```


```
class Meta141(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 141
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta141(metaclass=Meta141):
    def show_meta_id(self):
        return self.meta_id

obj141 = ClassWithMeta141()
obj141.show_meta_id()
```


```
class Meta142(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 142
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta142(metaclass=Meta142):
    def show_meta_id(self):
        return self.meta_id

obj142 = ClassWithMeta142()
obj142.show_meta_id()
```


```
class Meta143(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 143
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta143(metaclass=Meta143):
    def show_meta_id(self):
        return self.meta_id

obj143 = ClassWithMeta143()
obj143.show_meta_id()
```


```
class Meta144(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 144
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta144(metaclass=Meta144):
    def show_meta_id(self):
        return self.meta_id

obj144 = ClassWithMeta144()
obj144.show_meta_id()
```


```
class Meta145(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 145
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta145(metaclass=Meta145):
    def show_meta_id(self):
        return self.meta_id

obj145 = ClassWithMeta145()
obj145.show_meta_id()
```


```
class Meta146(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 146
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta146(metaclass=Meta146):
    def show_meta_id(self):
        return self.meta_id

obj146 = ClassWithMeta146()
obj146.show_meta_id()
```


```
class Meta147(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 147
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta147(metaclass=Meta147):
    def show_meta_id(self):
        return self.meta_id

obj147 = ClassWithMeta147()
obj147.show_meta_id()
```


```
class Meta148(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 148
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta148(metaclass=Meta148):
    def show_meta_id(self):
        return self.meta_id

obj148 = ClassWithMeta148()
obj148.show_meta_id()
```


```
class Meta149(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 149
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta149(metaclass=Meta149):
    def show_meta_id(self):
        return self.meta_id

obj149 = ClassWithMeta149()
obj149.show_meta_id()
```


```
class Meta150(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 150
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta150(metaclass=Meta150):
    def show_meta_id(self):
        return self.meta_id

obj150 = ClassWithMeta150()
obj150.show_meta_id()
```


```
class Meta151(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 151
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta151(metaclass=Meta151):
    def show_meta_id(self):
        return self.meta_id

obj151 = ClassWithMeta151()
obj151.show_meta_id()
```


```
class Meta152(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 152
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta152(metaclass=Meta152):
    def show_meta_id(self):
        return self.meta_id

obj152 = ClassWithMeta152()
obj152.show_meta_id()
```


```
class Meta153(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 153
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta153(metaclass=Meta153):
    def show_meta_id(self):
        return self.meta_id

obj153 = ClassWithMeta153()
obj153.show_meta_id()
```


```
class Meta154(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 154
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta154(metaclass=Meta154):
    def show_meta_id(self):
        return self.meta_id

obj154 = ClassWithMeta154()
obj154.show_meta_id()
```


```
class Meta155(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 155
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta155(metaclass=Meta155):
    def show_meta_id(self):
        return self.meta_id

obj155 = ClassWithMeta155()
obj155.show_meta_id()
```


```
class Meta156(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 156
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta156(metaclass=Meta156):
    def show_meta_id(self):
        return self.meta_id

obj156 = ClassWithMeta156()
obj156.show_meta_id()
```


```
class Meta157(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 157
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta157(metaclass=Meta157):
    def show_meta_id(self):
        return self.meta_id

obj157 = ClassWithMeta157()
obj157.show_meta_id()
```


```
class Meta158(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 158
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta158(metaclass=Meta158):
    def show_meta_id(self):
        return self.meta_id

obj158 = ClassWithMeta158()
obj158.show_meta_id()
```


```
class Meta159(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 159
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta159(metaclass=Meta159):
    def show_meta_id(self):
        return self.meta_id

obj159 = ClassWithMeta159()
obj159.show_meta_id()
```


```
class Meta160(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 160
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta160(metaclass=Meta160):
    def show_meta_id(self):
        return self.meta_id

obj160 = ClassWithMeta160()
obj160.show_meta_id()
```


```
class Meta161(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 161
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta161(metaclass=Meta161):
    def show_meta_id(self):
        return self.meta_id

obj161 = ClassWithMeta161()
obj161.show_meta_id()
```


```
class Meta162(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 162
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta162(metaclass=Meta162):
    def show_meta_id(self):
        return self.meta_id

obj162 = ClassWithMeta162()
obj162.show_meta_id()
```


```
class Meta163(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 163
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta163(metaclass=Meta163):
    def show_meta_id(self):
        return self.meta_id

obj163 = ClassWithMeta163()
obj163.show_meta_id()
```


```
class Meta164(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 164
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta164(metaclass=Meta164):
    def show_meta_id(self):
        return self.meta_id

obj164 = ClassWithMeta164()
obj164.show_meta_id()
```


```
class Meta165(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 165
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta165(metaclass=Meta165):
    def show_meta_id(self):
        return self.meta_id

obj165 = ClassWithMeta165()
obj165.show_meta_id()
```


```
class Meta166(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 166
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta166(metaclass=Meta166):
    def show_meta_id(self):
        return self.meta_id

obj166 = ClassWithMeta166()
obj166.show_meta_id()
```


```
class Meta167(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 167
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta167(metaclass=Meta167):
    def show_meta_id(self):
        return self.meta_id

obj167 = ClassWithMeta167()
obj167.show_meta_id()
```


```
class Meta168(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 168
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta168(metaclass=Meta168):
    def show_meta_id(self):
        return self.meta_id

obj168 = ClassWithMeta168()
obj168.show_meta_id()
```


```
class Meta169(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 169
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta169(metaclass=Meta169):
    def show_meta_id(self):
        return self.meta_id

obj169 = ClassWithMeta169()
obj169.show_meta_id()
```


```
class Meta170(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 170
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta170(metaclass=Meta170):
    def show_meta_id(self):
        return self.meta_id

obj170 = ClassWithMeta170()
obj170.show_meta_id()
```


```
class Meta171(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 171
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta171(metaclass=Meta171):
    def show_meta_id(self):
        return self.meta_id

obj171 = ClassWithMeta171()
obj171.show_meta_id()
```


```
class Meta172(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 172
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta172(metaclass=Meta172):
    def show_meta_id(self):
        return self.meta_id

obj172 = ClassWithMeta172()
obj172.show_meta_id()
```


```
class Meta173(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 173
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta173(metaclass=Meta173):
    def show_meta_id(self):
        return self.meta_id

obj173 = ClassWithMeta173()
obj173.show_meta_id()
```


```
class Meta174(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 174
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta174(metaclass=Meta174):
    def show_meta_id(self):
        return self.meta_id

obj174 = ClassWithMeta174()
obj174.show_meta_id()
```


```
class Meta175(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 175
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta175(metaclass=Meta175):
    def show_meta_id(self):
        return self.meta_id

obj175 = ClassWithMeta175()
obj175.show_meta_id()
```


```
class Meta176(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 176
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta176(metaclass=Meta176):
    def show_meta_id(self):
        return self.meta_id

obj176 = ClassWithMeta176()
obj176.show_meta_id()
```


```
class Meta177(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 177
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta177(metaclass=Meta177):
    def show_meta_id(self):
        return self.meta_id

obj177 = ClassWithMeta177()
obj177.show_meta_id()
```


```
class Meta178(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 178
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta178(metaclass=Meta178):
    def show_meta_id(self):
        return self.meta_id

obj178 = ClassWithMeta178()
obj178.show_meta_id()
```


```
class Meta179(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 179
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta179(metaclass=Meta179):
    def show_meta_id(self):
        return self.meta_id

obj179 = ClassWithMeta179()
obj179.show_meta_id()
```


```
class Meta180(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 180
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta180(metaclass=Meta180):
    def show_meta_id(self):
        return self.meta_id

obj180 = ClassWithMeta180()
obj180.show_meta_id()
```


```
class Meta181(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 181
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta181(metaclass=Meta181):
    def show_meta_id(self):
        return self.meta_id

obj181 = ClassWithMeta181()
obj181.show_meta_id()
```


```
class Meta182(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 182
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta182(metaclass=Meta182):
    def show_meta_id(self):
        return self.meta_id

obj182 = ClassWithMeta182()
obj182.show_meta_id()
```


```
class Meta183(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 183
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta183(metaclass=Meta183):
    def show_meta_id(self):
        return self.meta_id

obj183 = ClassWithMeta183()
obj183.show_meta_id()
```


```
class Meta184(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 184
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta184(metaclass=Meta184):
    def show_meta_id(self):
        return self.meta_id

obj184 = ClassWithMeta184()
obj184.show_meta_id()
```


```
class Meta185(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 185
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta185(metaclass=Meta185):
    def show_meta_id(self):
        return self.meta_id

obj185 = ClassWithMeta185()
obj185.show_meta_id()
```


```
class Meta186(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 186
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta186(metaclass=Meta186):
    def show_meta_id(self):
        return self.meta_id

obj186 = ClassWithMeta186()
obj186.show_meta_id()
```


```
class Meta187(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 187
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta187(metaclass=Meta187):
    def show_meta_id(self):
        return self.meta_id

obj187 = ClassWithMeta187()
obj187.show_meta_id()
```


```
class Meta188(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 188
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta188(metaclass=Meta188):
    def show_meta_id(self):
        return self.meta_id

obj188 = ClassWithMeta188()
obj188.show_meta_id()
```


```
class Meta189(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 189
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta189(metaclass=Meta189):
    def show_meta_id(self):
        return self.meta_id

obj189 = ClassWithMeta189()
obj189.show_meta_id()
```


```
class Meta190(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 190
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta190(metaclass=Meta190):
    def show_meta_id(self):
        return self.meta_id

obj190 = ClassWithMeta190()
obj190.show_meta_id()
```


```
class Meta191(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 191
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta191(metaclass=Meta191):
    def show_meta_id(self):
        return self.meta_id

obj191 = ClassWithMeta191()
obj191.show_meta_id()
```


```
class Meta192(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 192
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta192(metaclass=Meta192):
    def show_meta_id(self):
        return self.meta_id

obj192 = ClassWithMeta192()
obj192.show_meta_id()
```


```
class Meta193(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 193
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta193(metaclass=Meta193):
    def show_meta_id(self):
        return self.meta_id

obj193 = ClassWithMeta193()
obj193.show_meta_id()
```


```
class Meta194(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 194
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta194(metaclass=Meta194):
    def show_meta_id(self):
        return self.meta_id

obj194 = ClassWithMeta194()
obj194.show_meta_id()
```


```
class Meta195(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 195
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta195(metaclass=Meta195):
    def show_meta_id(self):
        return self.meta_id

obj195 = ClassWithMeta195()
obj195.show_meta_id()
```


```
class Meta196(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 196
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta196(metaclass=Meta196):
    def show_meta_id(self):
        return self.meta_id

obj196 = ClassWithMeta196()
obj196.show_meta_id()
```


```
class Meta197(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 197
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta197(metaclass=Meta197):
    def show_meta_id(self):
        return self.meta_id

obj197 = ClassWithMeta197()
obj197.show_meta_id()
```


```
class Meta198(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 198
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta198(metaclass=Meta198):
    def show_meta_id(self):
        return self.meta_id

obj198 = ClassWithMeta198()
obj198.show_meta_id()
```


```
class Meta199(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 199
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta199(metaclass=Meta199):
    def show_meta_id(self):
        return self.meta_id

obj199 = ClassWithMeta199()
obj199.show_meta_id()
```


```
class Meta200(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 200
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta200(metaclass=Meta200):
    def show_meta_id(self):
        return self.meta_id

obj200 = ClassWithMeta200()
obj200.show_meta_id()
```


```
class Meta201(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 201
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta201(metaclass=Meta201):
    def show_meta_id(self):
        return self.meta_id

obj201 = ClassWithMeta201()
obj201.show_meta_id()
```


```
class Meta202(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 202
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta202(metaclass=Meta202):
    def show_meta_id(self):
        return self.meta_id

obj202 = ClassWithMeta202()
obj202.show_meta_id()
```


```
class Meta203(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 203
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta203(metaclass=Meta203):
    def show_meta_id(self):
        return self.meta_id

obj203 = ClassWithMeta203()
obj203.show_meta_id()
```


```
class Meta204(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 204
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta204(metaclass=Meta204):
    def show_meta_id(self):
        return self.meta_id

obj204 = ClassWithMeta204()
obj204.show_meta_id()
```


```
class Meta205(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 205
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta205(metaclass=Meta205):
    def show_meta_id(self):
        return self.meta_id

obj205 = ClassWithMeta205()
obj205.show_meta_id()
```


```
class Meta206(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 206
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta206(metaclass=Meta206):
    def show_meta_id(self):
        return self.meta_id

obj206 = ClassWithMeta206()
obj206.show_meta_id()
```


```
class Meta207(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 207
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta207(metaclass=Meta207):
    def show_meta_id(self):
        return self.meta_id

obj207 = ClassWithMeta207()
obj207.show_meta_id()
```


```
class Meta208(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 208
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta208(metaclass=Meta208):
    def show_meta_id(self):
        return self.meta_id

obj208 = ClassWithMeta208()
obj208.show_meta_id()
```


```
class Meta209(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 209
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta209(metaclass=Meta209):
    def show_meta_id(self):
        return self.meta_id

obj209 = ClassWithMeta209()
obj209.show_meta_id()
```


```
class Meta210(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 210
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta210(metaclass=Meta210):
    def show_meta_id(self):
        return self.meta_id

obj210 = ClassWithMeta210()
obj210.show_meta_id()
```


```
class Meta211(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 211
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta211(metaclass=Meta211):
    def show_meta_id(self):
        return self.meta_id

obj211 = ClassWithMeta211()
obj211.show_meta_id()
```


```
class Meta212(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 212
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta212(metaclass=Meta212):
    def show_meta_id(self):
        return self.meta_id

obj212 = ClassWithMeta212()
obj212.show_meta_id()
```


```
class Meta213(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 213
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta213(metaclass=Meta213):
    def show_meta_id(self):
        return self.meta_id

obj213 = ClassWithMeta213()
obj213.show_meta_id()
```


```
class Meta214(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 214
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta214(metaclass=Meta214):
    def show_meta_id(self):
        return self.meta_id

obj214 = ClassWithMeta214()
obj214.show_meta_id()
```


```
class Meta215(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 215
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta215(metaclass=Meta215):
    def show_meta_id(self):
        return self.meta_id

obj215 = ClassWithMeta215()
obj215.show_meta_id()
```


```
class Meta216(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 216
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta216(metaclass=Meta216):
    def show_meta_id(self):
        return self.meta_id

obj216 = ClassWithMeta216()
obj216.show_meta_id()
```


```
class Meta217(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 217
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta217(metaclass=Meta217):
    def show_meta_id(self):
        return self.meta_id

obj217 = ClassWithMeta217()
obj217.show_meta_id()
```


```
class Meta218(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 218
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta218(metaclass=Meta218):
    def show_meta_id(self):
        return self.meta_id

obj218 = ClassWithMeta218()
obj218.show_meta_id()
```


```
class Meta219(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 219
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta219(metaclass=Meta219):
    def show_meta_id(self):
        return self.meta_id

obj219 = ClassWithMeta219()
obj219.show_meta_id()
```


```
class Meta220(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 220
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta220(metaclass=Meta220):
    def show_meta_id(self):
        return self.meta_id

obj220 = ClassWithMeta220()
obj220.show_meta_id()
```


```
class Meta221(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 221
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta221(metaclass=Meta221):
    def show_meta_id(self):
        return self.meta_id

obj221 = ClassWithMeta221()
obj221.show_meta_id()
```


```
class Meta222(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 222
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta222(metaclass=Meta222):
    def show_meta_id(self):
        return self.meta_id

obj222 = ClassWithMeta222()
obj222.show_meta_id()
```


```
class Meta223(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 223
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta223(metaclass=Meta223):
    def show_meta_id(self):
        return self.meta_id

obj223 = ClassWithMeta223()
obj223.show_meta_id()
```


```
class Meta224(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 224
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta224(metaclass=Meta224):
    def show_meta_id(self):
        return self.meta_id

obj224 = ClassWithMeta224()
obj224.show_meta_id()
```


```
class Meta225(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 225
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta225(metaclass=Meta225):
    def show_meta_id(self):
        return self.meta_id

obj225 = ClassWithMeta225()
obj225.show_meta_id()
```


```
class Meta226(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 226
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta226(metaclass=Meta226):
    def show_meta_id(self):
        return self.meta_id

obj226 = ClassWithMeta226()
obj226.show_meta_id()
```


```
class Meta227(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 227
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta227(metaclass=Meta227):
    def show_meta_id(self):
        return self.meta_id

obj227 = ClassWithMeta227()
obj227.show_meta_id()
```


```
class Meta228(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 228
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta228(metaclass=Meta228):
    def show_meta_id(self):
        return self.meta_id

obj228 = ClassWithMeta228()
obj228.show_meta_id()
```


```
class Meta229(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 229
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta229(metaclass=Meta229):
    def show_meta_id(self):
        return self.meta_id

obj229 = ClassWithMeta229()
obj229.show_meta_id()
```


```
class Meta230(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 230
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta230(metaclass=Meta230):
    def show_meta_id(self):
        return self.meta_id

obj230 = ClassWithMeta230()
obj230.show_meta_id()
```


```
class Meta231(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 231
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta231(metaclass=Meta231):
    def show_meta_id(self):
        return self.meta_id

obj231 = ClassWithMeta231()
obj231.show_meta_id()
```


```
class Meta232(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 232
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta232(metaclass=Meta232):
    def show_meta_id(self):
        return self.meta_id

obj232 = ClassWithMeta232()
obj232.show_meta_id()
```


```
class Meta233(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 233
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta233(metaclass=Meta233):
    def show_meta_id(self):
        return self.meta_id

obj233 = ClassWithMeta233()
obj233.show_meta_id()
```


```
class Meta234(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 234
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta234(metaclass=Meta234):
    def show_meta_id(self):
        return self.meta_id

obj234 = ClassWithMeta234()
obj234.show_meta_id()
```


```
class Meta235(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 235
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta235(metaclass=Meta235):
    def show_meta_id(self):
        return self.meta_id

obj235 = ClassWithMeta235()
obj235.show_meta_id()
```


```
class Meta236(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 236
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta236(metaclass=Meta236):
    def show_meta_id(self):
        return self.meta_id

obj236 = ClassWithMeta236()
obj236.show_meta_id()
```


```
class Meta237(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 237
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta237(metaclass=Meta237):
    def show_meta_id(self):
        return self.meta_id

obj237 = ClassWithMeta237()
obj237.show_meta_id()
```


```
class Meta238(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 238
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta238(metaclass=Meta238):
    def show_meta_id(self):
        return self.meta_id

obj238 = ClassWithMeta238()
obj238.show_meta_id()
```


```
class Meta239(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 239
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta239(metaclass=Meta239):
    def show_meta_id(self):
        return self.meta_id

obj239 = ClassWithMeta239()
obj239.show_meta_id()
```


```
class Meta240(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 240
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta240(metaclass=Meta240):
    def show_meta_id(self):
        return self.meta_id

obj240 = ClassWithMeta240()
obj240.show_meta_id()
```


```
class Meta241(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 241
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta241(metaclass=Meta241):
    def show_meta_id(self):
        return self.meta_id

obj241 = ClassWithMeta241()
obj241.show_meta_id()
```


```
class Meta242(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 242
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta242(metaclass=Meta242):
    def show_meta_id(self):
        return self.meta_id

obj242 = ClassWithMeta242()
obj242.show_meta_id()
```


```
class Meta243(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 243
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta243(metaclass=Meta243):
    def show_meta_id(self):
        return self.meta_id

obj243 = ClassWithMeta243()
obj243.show_meta_id()
```


```
class Meta244(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 244
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta244(metaclass=Meta244):
    def show_meta_id(self):
        return self.meta_id

obj244 = ClassWithMeta244()
obj244.show_meta_id()
```


```
class Meta245(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 245
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta245(metaclass=Meta245):
    def show_meta_id(self):
        return self.meta_id

obj245 = ClassWithMeta245()
obj245.show_meta_id()
```


```
class Meta246(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 246
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta246(metaclass=Meta246):
    def show_meta_id(self):
        return self.meta_id

obj246 = ClassWithMeta246()
obj246.show_meta_id()
```


```
class Meta247(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 247
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta247(metaclass=Meta247):
    def show_meta_id(self):
        return self.meta_id

obj247 = ClassWithMeta247()
obj247.show_meta_id()
```


```
class Meta248(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 248
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta248(metaclass=Meta248):
    def show_meta_id(self):
        return self.meta_id

obj248 = ClassWithMeta248()
obj248.show_meta_id()
```


```
class Meta249(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 249
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta249(metaclass=Meta249):
    def show_meta_id(self):
        return self.meta_id

obj249 = ClassWithMeta249()
obj249.show_meta_id()
```


```
class Meta250(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 250
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta250(metaclass=Meta250):
    def show_meta_id(self):
        return self.meta_id

obj250 = ClassWithMeta250()
obj250.show_meta_id()
```


```
class Meta251(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 251
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta251(metaclass=Meta251):
    def show_meta_id(self):
        return self.meta_id

obj251 = ClassWithMeta251()
obj251.show_meta_id()
```


```
class Meta252(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 252
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta252(metaclass=Meta252):
    def show_meta_id(self):
        return self.meta_id

obj252 = ClassWithMeta252()
obj252.show_meta_id()
```


```
class Meta253(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 253
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta253(metaclass=Meta253):
    def show_meta_id(self):
        return self.meta_id

obj253 = ClassWithMeta253()
obj253.show_meta_id()
```


```
class Meta254(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 254
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta254(metaclass=Meta254):
    def show_meta_id(self):
        return self.meta_id

obj254 = ClassWithMeta254()
obj254.show_meta_id()
```


```
class Meta255(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 255
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta255(metaclass=Meta255):
    def show_meta_id(self):
        return self.meta_id

obj255 = ClassWithMeta255()
obj255.show_meta_id()
```


```
class Meta256(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 256
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta256(metaclass=Meta256):
    def show_meta_id(self):
        return self.meta_id

obj256 = ClassWithMeta256()
obj256.show_meta_id()
```


```
class Meta257(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 257
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta257(metaclass=Meta257):
    def show_meta_id(self):
        return self.meta_id

obj257 = ClassWithMeta257()
obj257.show_meta_id()
```


```
class Meta258(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 258
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta258(metaclass=Meta258):
    def show_meta_id(self):
        return self.meta_id

obj258 = ClassWithMeta258()
obj258.show_meta_id()
```


```
class Meta259(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 259
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta259(metaclass=Meta259):
    def show_meta_id(self):
        return self.meta_id

obj259 = ClassWithMeta259()
obj259.show_meta_id()
```


```
class Meta260(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 260
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta260(metaclass=Meta260):
    def show_meta_id(self):
        return self.meta_id

obj260 = ClassWithMeta260()
obj260.show_meta_id()
```


```
class Meta261(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 261
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta261(metaclass=Meta261):
    def show_meta_id(self):
        return self.meta_id

obj261 = ClassWithMeta261()
obj261.show_meta_id()
```


```
class Meta262(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 262
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta262(metaclass=Meta262):
    def show_meta_id(self):
        return self.meta_id

obj262 = ClassWithMeta262()
obj262.show_meta_id()
```


```
class Meta263(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 263
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta263(metaclass=Meta263):
    def show_meta_id(self):
        return self.meta_id

obj263 = ClassWithMeta263()
obj263.show_meta_id()
```


```
class Meta264(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 264
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta264(metaclass=Meta264):
    def show_meta_id(self):
        return self.meta_id

obj264 = ClassWithMeta264()
obj264.show_meta_id()
```


```
class Meta265(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 265
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta265(metaclass=Meta265):
    def show_meta_id(self):
        return self.meta_id

obj265 = ClassWithMeta265()
obj265.show_meta_id()
```


```
class Meta266(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 266
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta266(metaclass=Meta266):
    def show_meta_id(self):
        return self.meta_id

obj266 = ClassWithMeta266()
obj266.show_meta_id()
```


```
class Meta267(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 267
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta267(metaclass=Meta267):
    def show_meta_id(self):
        return self.meta_id

obj267 = ClassWithMeta267()
obj267.show_meta_id()
```


```
class Meta268(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 268
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta268(metaclass=Meta268):
    def show_meta_id(self):
        return self.meta_id

obj268 = ClassWithMeta268()
obj268.show_meta_id()
```


```
class Meta269(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 269
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta269(metaclass=Meta269):
    def show_meta_id(self):
        return self.meta_id

obj269 = ClassWithMeta269()
obj269.show_meta_id()
```


```
class Meta270(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 270
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta270(metaclass=Meta270):
    def show_meta_id(self):
        return self.meta_id

obj270 = ClassWithMeta270()
obj270.show_meta_id()
```


```
class Meta271(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 271
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta271(metaclass=Meta271):
    def show_meta_id(self):
        return self.meta_id

obj271 = ClassWithMeta271()
obj271.show_meta_id()
```


```
class Meta272(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 272
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta272(metaclass=Meta272):
    def show_meta_id(self):
        return self.meta_id

obj272 = ClassWithMeta272()
obj272.show_meta_id()
```


```
class Meta273(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 273
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta273(metaclass=Meta273):
    def show_meta_id(self):
        return self.meta_id

obj273 = ClassWithMeta273()
obj273.show_meta_id()
```


```
class Meta274(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 274
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta274(metaclass=Meta274):
    def show_meta_id(self):
        return self.meta_id

obj274 = ClassWithMeta274()
obj274.show_meta_id()
```


```
class Meta275(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 275
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta275(metaclass=Meta275):
    def show_meta_id(self):
        return self.meta_id

obj275 = ClassWithMeta275()
obj275.show_meta_id()
```


```
class Meta276(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 276
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta276(metaclass=Meta276):
    def show_meta_id(self):
        return self.meta_id

obj276 = ClassWithMeta276()
obj276.show_meta_id()
```


```
class Meta277(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 277
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta277(metaclass=Meta277):
    def show_meta_id(self):
        return self.meta_id

obj277 = ClassWithMeta277()
obj277.show_meta_id()
```


```
class Meta278(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 278
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta278(metaclass=Meta278):
    def show_meta_id(self):
        return self.meta_id

obj278 = ClassWithMeta278()
obj278.show_meta_id()
```


```
class Meta279(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 279
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta279(metaclass=Meta279):
    def show_meta_id(self):
        return self.meta_id

obj279 = ClassWithMeta279()
obj279.show_meta_id()
```


```
class Meta280(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 280
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta280(metaclass=Meta280):
    def show_meta_id(self):
        return self.meta_id

obj280 = ClassWithMeta280()
obj280.show_meta_id()
```


```
class Meta281(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 281
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta281(metaclass=Meta281):
    def show_meta_id(self):
        return self.meta_id

obj281 = ClassWithMeta281()
obj281.show_meta_id()
```


```
class Meta282(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 282
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta282(metaclass=Meta282):
    def show_meta_id(self):
        return self.meta_id

obj282 = ClassWithMeta282()
obj282.show_meta_id()
```


```
class Meta283(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 283
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta283(metaclass=Meta283):
    def show_meta_id(self):
        return self.meta_id

obj283 = ClassWithMeta283()
obj283.show_meta_id()
```


```
class Meta284(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 284
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta284(metaclass=Meta284):
    def show_meta_id(self):
        return self.meta_id

obj284 = ClassWithMeta284()
obj284.show_meta_id()
```


```
class Meta285(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 285
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta285(metaclass=Meta285):
    def show_meta_id(self):
        return self.meta_id

obj285 = ClassWithMeta285()
obj285.show_meta_id()
```


```
class Meta286(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 286
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta286(metaclass=Meta286):
    def show_meta_id(self):
        return self.meta_id

obj286 = ClassWithMeta286()
obj286.show_meta_id()
```


```
class Meta287(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 287
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta287(metaclass=Meta287):
    def show_meta_id(self):
        return self.meta_id

obj287 = ClassWithMeta287()
obj287.show_meta_id()
```


```
class Meta288(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 288
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta288(metaclass=Meta288):
    def show_meta_id(self):
        return self.meta_id

obj288 = ClassWithMeta288()
obj288.show_meta_id()
```


```
class Meta289(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 289
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta289(metaclass=Meta289):
    def show_meta_id(self):
        return self.meta_id

obj289 = ClassWithMeta289()
obj289.show_meta_id()
```


```
class Meta290(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 290
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta290(metaclass=Meta290):
    def show_meta_id(self):
        return self.meta_id

obj290 = ClassWithMeta290()
obj290.show_meta_id()
```


```
class Meta291(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 291
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta291(metaclass=Meta291):
    def show_meta_id(self):
        return self.meta_id

obj291 = ClassWithMeta291()
obj291.show_meta_id()
```


```
class Meta292(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 292
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta292(metaclass=Meta292):
    def show_meta_id(self):
        return self.meta_id

obj292 = ClassWithMeta292()
obj292.show_meta_id()
```


```
class Meta293(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 293
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta293(metaclass=Meta293):
    def show_meta_id(self):
        return self.meta_id

obj293 = ClassWithMeta293()
obj293.show_meta_id()
```


```
class Meta294(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 294
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta294(metaclass=Meta294):
    def show_meta_id(self):
        return self.meta_id

obj294 = ClassWithMeta294()
obj294.show_meta_id()
```


```
class Meta295(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 295
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta295(metaclass=Meta295):
    def show_meta_id(self):
        return self.meta_id

obj295 = ClassWithMeta295()
obj295.show_meta_id()
```


```
class Meta296(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 296
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta296(metaclass=Meta296):
    def show_meta_id(self):
        return self.meta_id

obj296 = ClassWithMeta296()
obj296.show_meta_id()
```


```
class Meta297(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 297
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta297(metaclass=Meta297):
    def show_meta_id(self):
        return self.meta_id

obj297 = ClassWithMeta297()
obj297.show_meta_id()
```


```
class Meta298(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 298
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta298(metaclass=Meta298):
    def show_meta_id(self):
        return self.meta_id

obj298 = ClassWithMeta298()
obj298.show_meta_id()
```


```
class Meta299(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 299
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta299(metaclass=Meta299):
    def show_meta_id(self):
        return self.meta_id

obj299 = ClassWithMeta299()
obj299.show_meta_id()
```


```
class Meta300(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 300
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta300(metaclass=Meta300):
    def show_meta_id(self):
        return self.meta_id

obj300 = ClassWithMeta300()
obj300.show_meta_id()
```


```
class Meta301(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 301
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta301(metaclass=Meta301):
    def show_meta_id(self):
        return self.meta_id

obj301 = ClassWithMeta301()
obj301.show_meta_id()
```


```
class Meta302(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 302
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta302(metaclass=Meta302):
    def show_meta_id(self):
        return self.meta_id

obj302 = ClassWithMeta302()
obj302.show_meta_id()
```


```
class Meta303(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 303
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta303(metaclass=Meta303):
    def show_meta_id(self):
        return self.meta_id

obj303 = ClassWithMeta303()
obj303.show_meta_id()
```


```
class Meta304(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 304
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta304(metaclass=Meta304):
    def show_meta_id(self):
        return self.meta_id

obj304 = ClassWithMeta304()
obj304.show_meta_id()
```


```
class Meta305(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 305
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta305(metaclass=Meta305):
    def show_meta_id(self):
        return self.meta_id

obj305 = ClassWithMeta305()
obj305.show_meta_id()
```


```
class Meta306(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 306
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta306(metaclass=Meta306):
    def show_meta_id(self):
        return self.meta_id

obj306 = ClassWithMeta306()
obj306.show_meta_id()
```


```
class Meta307(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 307
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta307(metaclass=Meta307):
    def show_meta_id(self):
        return self.meta_id

obj307 = ClassWithMeta307()
obj307.show_meta_id()
```


```
class Meta308(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 308
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta308(metaclass=Meta308):
    def show_meta_id(self):
        return self.meta_id

obj308 = ClassWithMeta308()
obj308.show_meta_id()
```


```
class Meta309(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 309
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta309(metaclass=Meta309):
    def show_meta_id(self):
        return self.meta_id

obj309 = ClassWithMeta309()
obj309.show_meta_id()
```


```
class Meta310(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 310
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta310(metaclass=Meta310):
    def show_meta_id(self):
        return self.meta_id

obj310 = ClassWithMeta310()
obj310.show_meta_id()
```


```
class Meta311(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 311
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta311(metaclass=Meta311):
    def show_meta_id(self):
        return self.meta_id

obj311 = ClassWithMeta311()
obj311.show_meta_id()
```


```
class Meta312(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 312
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta312(metaclass=Meta312):
    def show_meta_id(self):
        return self.meta_id

obj312 = ClassWithMeta312()
obj312.show_meta_id()
```


```
class Meta313(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 313
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta313(metaclass=Meta313):
    def show_meta_id(self):
        return self.meta_id

obj313 = ClassWithMeta313()
obj313.show_meta_id()
```


```
class Meta314(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 314
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta314(metaclass=Meta314):
    def show_meta_id(self):
        return self.meta_id

obj314 = ClassWithMeta314()
obj314.show_meta_id()
```


```
class Meta315(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 315
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta315(metaclass=Meta315):
    def show_meta_id(self):
        return self.meta_id

obj315 = ClassWithMeta315()
obj315.show_meta_id()
```


```
class Meta316(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 316
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta316(metaclass=Meta316):
    def show_meta_id(self):
        return self.meta_id

obj316 = ClassWithMeta316()
obj316.show_meta_id()
```


```
class Meta317(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 317
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta317(metaclass=Meta317):
    def show_meta_id(self):
        return self.meta_id

obj317 = ClassWithMeta317()
obj317.show_meta_id()
```


```
class Meta318(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 318
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta318(metaclass=Meta318):
    def show_meta_id(self):
        return self.meta_id

obj318 = ClassWithMeta318()
obj318.show_meta_id()
```


```
class Meta319(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 319
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta319(metaclass=Meta319):
    def show_meta_id(self):
        return self.meta_id

obj319 = ClassWithMeta319()
obj319.show_meta_id()
```


```
class Meta320(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 320
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta320(metaclass=Meta320):
    def show_meta_id(self):
        return self.meta_id

obj320 = ClassWithMeta320()
obj320.show_meta_id()
```


```
class Meta321(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 321
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta321(metaclass=Meta321):
    def show_meta_id(self):
        return self.meta_id

obj321 = ClassWithMeta321()
obj321.show_meta_id()
```


```
class Meta322(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 322
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta322(metaclass=Meta322):
    def show_meta_id(self):
        return self.meta_id

obj322 = ClassWithMeta322()
obj322.show_meta_id()
```


```
class Meta323(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 323
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta323(metaclass=Meta323):
    def show_meta_id(self):
        return self.meta_id

obj323 = ClassWithMeta323()
obj323.show_meta_id()
```


```
class Meta324(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 324
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta324(metaclass=Meta324):
    def show_meta_id(self):
        return self.meta_id

obj324 = ClassWithMeta324()
obj324.show_meta_id()
```


```
class Meta325(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 325
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta325(metaclass=Meta325):
    def show_meta_id(self):
        return self.meta_id

obj325 = ClassWithMeta325()
obj325.show_meta_id()
```


```
class Meta326(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 326
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta326(metaclass=Meta326):
    def show_meta_id(self):
        return self.meta_id

obj326 = ClassWithMeta326()
obj326.show_meta_id()
```


```
class Meta327(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 327
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta327(metaclass=Meta327):
    def show_meta_id(self):
        return self.meta_id

obj327 = ClassWithMeta327()
obj327.show_meta_id()
```


```
class Meta328(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 328
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta328(metaclass=Meta328):
    def show_meta_id(self):
        return self.meta_id

obj328 = ClassWithMeta328()
obj328.show_meta_id()
```


```
class Meta329(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 329
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta329(metaclass=Meta329):
    def show_meta_id(self):
        return self.meta_id

obj329 = ClassWithMeta329()
obj329.show_meta_id()
```


```
class Meta330(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 330
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta330(metaclass=Meta330):
    def show_meta_id(self):
        return self.meta_id

obj330 = ClassWithMeta330()
obj330.show_meta_id()
```


```
class Meta331(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 331
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta331(metaclass=Meta331):
    def show_meta_id(self):
        return self.meta_id

obj331 = ClassWithMeta331()
obj331.show_meta_id()
```


```
class Meta332(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 332
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta332(metaclass=Meta332):
    def show_meta_id(self):
        return self.meta_id

obj332 = ClassWithMeta332()
obj332.show_meta_id()
```


```
class Meta333(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 333
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta333(metaclass=Meta333):
    def show_meta_id(self):
        return self.meta_id

obj333 = ClassWithMeta333()
obj333.show_meta_id()
```


```
class Meta334(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 334
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta334(metaclass=Meta334):
    def show_meta_id(self):
        return self.meta_id

obj334 = ClassWithMeta334()
obj334.show_meta_id()
```


```
class Meta335(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 335
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta335(metaclass=Meta335):
    def show_meta_id(self):
        return self.meta_id

obj335 = ClassWithMeta335()
obj335.show_meta_id()
```


```
class Meta336(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 336
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta336(metaclass=Meta336):
    def show_meta_id(self):
        return self.meta_id

obj336 = ClassWithMeta336()
obj336.show_meta_id()
```


```
class Meta337(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 337
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta337(metaclass=Meta337):
    def show_meta_id(self):
        return self.meta_id

obj337 = ClassWithMeta337()
obj337.show_meta_id()
```


```
class Meta338(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 338
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta338(metaclass=Meta338):
    def show_meta_id(self):
        return self.meta_id

obj338 = ClassWithMeta338()
obj338.show_meta_id()
```


```
class Meta339(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 339
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta339(metaclass=Meta339):
    def show_meta_id(self):
        return self.meta_id

obj339 = ClassWithMeta339()
obj339.show_meta_id()
```


```
class Meta340(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 340
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta340(metaclass=Meta340):
    def show_meta_id(self):
        return self.meta_id

obj340 = ClassWithMeta340()
obj340.show_meta_id()
```


```
class Meta341(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 341
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta341(metaclass=Meta341):
    def show_meta_id(self):
        return self.meta_id

obj341 = ClassWithMeta341()
obj341.show_meta_id()
```


```
class Meta342(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 342
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta342(metaclass=Meta342):
    def show_meta_id(self):
        return self.meta_id

obj342 = ClassWithMeta342()
obj342.show_meta_id()
```


```
class Meta343(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 343
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta343(metaclass=Meta343):
    def show_meta_id(self):
        return self.meta_id

obj343 = ClassWithMeta343()
obj343.show_meta_id()
```


```
class Meta344(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 344
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta344(metaclass=Meta344):
    def show_meta_id(self):
        return self.meta_id

obj344 = ClassWithMeta344()
obj344.show_meta_id()
```


```
class Meta345(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 345
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta345(metaclass=Meta345):
    def show_meta_id(self):
        return self.meta_id

obj345 = ClassWithMeta345()
obj345.show_meta_id()
```


```
class Meta346(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 346
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta346(metaclass=Meta346):
    def show_meta_id(self):
        return self.meta_id

obj346 = ClassWithMeta346()
obj346.show_meta_id()
```


```
class Meta347(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 347
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta347(metaclass=Meta347):
    def show_meta_id(self):
        return self.meta_id

obj347 = ClassWithMeta347()
obj347.show_meta_id()
```


```
class Meta348(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 348
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta348(metaclass=Meta348):
    def show_meta_id(self):
        return self.meta_id

obj348 = ClassWithMeta348()
obj348.show_meta_id()
```


```
class Meta349(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 349
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta349(metaclass=Meta349):
    def show_meta_id(self):
        return self.meta_id

obj349 = ClassWithMeta349()
obj349.show_meta_id()
```


```
class Meta350(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 350
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta350(metaclass=Meta350):
    def show_meta_id(self):
        return self.meta_id

obj350 = ClassWithMeta350()
obj350.show_meta_id()
```


```
class Meta351(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 351
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta351(metaclass=Meta351):
    def show_meta_id(self):
        return self.meta_id

obj351 = ClassWithMeta351()
obj351.show_meta_id()
```


```
class Meta352(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 352
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta352(metaclass=Meta352):
    def show_meta_id(self):
        return self.meta_id

obj352 = ClassWithMeta352()
obj352.show_meta_id()
```


```
class Meta353(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 353
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta353(metaclass=Meta353):
    def show_meta_id(self):
        return self.meta_id

obj353 = ClassWithMeta353()
obj353.show_meta_id()
```


```
class Meta354(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 354
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta354(metaclass=Meta354):
    def show_meta_id(self):
        return self.meta_id

obj354 = ClassWithMeta354()
obj354.show_meta_id()
```


```
class Meta355(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 355
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta355(metaclass=Meta355):
    def show_meta_id(self):
        return self.meta_id

obj355 = ClassWithMeta355()
obj355.show_meta_id()
```


```
class Meta356(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 356
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta356(metaclass=Meta356):
    def show_meta_id(self):
        return self.meta_id

obj356 = ClassWithMeta356()
obj356.show_meta_id()
```


```
class Meta357(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 357
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta357(metaclass=Meta357):
    def show_meta_id(self):
        return self.meta_id

obj357 = ClassWithMeta357()
obj357.show_meta_id()
```


```
class Meta358(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 358
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta358(metaclass=Meta358):
    def show_meta_id(self):
        return self.meta_id

obj358 = ClassWithMeta358()
obj358.show_meta_id()
```


```
class Meta359(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 359
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta359(metaclass=Meta359):
    def show_meta_id(self):
        return self.meta_id

obj359 = ClassWithMeta359()
obj359.show_meta_id()
```


```
class Meta360(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 360
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta360(metaclass=Meta360):
    def show_meta_id(self):
        return self.meta_id

obj360 = ClassWithMeta360()
obj360.show_meta_id()
```


```
class Meta361(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 361
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta361(metaclass=Meta361):
    def show_meta_id(self):
        return self.meta_id

obj361 = ClassWithMeta361()
obj361.show_meta_id()
```


```
class Meta362(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 362
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta362(metaclass=Meta362):
    def show_meta_id(self):
        return self.meta_id

obj362 = ClassWithMeta362()
obj362.show_meta_id()
```


```
class Meta363(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 363
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta363(metaclass=Meta363):
    def show_meta_id(self):
        return self.meta_id

obj363 = ClassWithMeta363()
obj363.show_meta_id()
```


```
class Meta364(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 364
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta364(metaclass=Meta364):
    def show_meta_id(self):
        return self.meta_id

obj364 = ClassWithMeta364()
obj364.show_meta_id()
```


```
class Meta365(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 365
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta365(metaclass=Meta365):
    def show_meta_id(self):
        return self.meta_id

obj365 = ClassWithMeta365()
obj365.show_meta_id()
```


```
class Meta366(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 366
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta366(metaclass=Meta366):
    def show_meta_id(self):
        return self.meta_id

obj366 = ClassWithMeta366()
obj366.show_meta_id()
```


```
class Meta367(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 367
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta367(metaclass=Meta367):
    def show_meta_id(self):
        return self.meta_id

obj367 = ClassWithMeta367()
obj367.show_meta_id()
```


```
class Meta368(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 368
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta368(metaclass=Meta368):
    def show_meta_id(self):
        return self.meta_id

obj368 = ClassWithMeta368()
obj368.show_meta_id()
```


```
class Meta369(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 369
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta369(metaclass=Meta369):
    def show_meta_id(self):
        return self.meta_id

obj369 = ClassWithMeta369()
obj369.show_meta_id()
```


```
class Meta370(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 370
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta370(metaclass=Meta370):
    def show_meta_id(self):
        return self.meta_id

obj370 = ClassWithMeta370()
obj370.show_meta_id()
```


```
class Meta371(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 371
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta371(metaclass=Meta371):
    def show_meta_id(self):
        return self.meta_id

obj371 = ClassWithMeta371()
obj371.show_meta_id()
```


```
class Meta372(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 372
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta372(metaclass=Meta372):
    def show_meta_id(self):
        return self.meta_id

obj372 = ClassWithMeta372()
obj372.show_meta_id()
```


```
class Meta373(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 373
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta373(metaclass=Meta373):
    def show_meta_id(self):
        return self.meta_id

obj373 = ClassWithMeta373()
obj373.show_meta_id()
```


```
class Meta374(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 374
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta374(metaclass=Meta374):
    def show_meta_id(self):
        return self.meta_id

obj374 = ClassWithMeta374()
obj374.show_meta_id()
```


```
class Meta375(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 375
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta375(metaclass=Meta375):
    def show_meta_id(self):
        return self.meta_id

obj375 = ClassWithMeta375()
obj375.show_meta_id()
```


```
class Meta376(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 376
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta376(metaclass=Meta376):
    def show_meta_id(self):
        return self.meta_id

obj376 = ClassWithMeta376()
obj376.show_meta_id()
```


```
class Meta377(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 377
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta377(metaclass=Meta377):
    def show_meta_id(self):
        return self.meta_id

obj377 = ClassWithMeta377()
obj377.show_meta_id()
```


```
class Meta378(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 378
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta378(metaclass=Meta378):
    def show_meta_id(self):
        return self.meta_id

obj378 = ClassWithMeta378()
obj378.show_meta_id()
```


```
class Meta379(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 379
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta379(metaclass=Meta379):
    def show_meta_id(self):
        return self.meta_id

obj379 = ClassWithMeta379()
obj379.show_meta_id()
```


```
class Meta380(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 380
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta380(metaclass=Meta380):
    def show_meta_id(self):
        return self.meta_id

obj380 = ClassWithMeta380()
obj380.show_meta_id()
```


```
class Meta381(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 381
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta381(metaclass=Meta381):
    def show_meta_id(self):
        return self.meta_id

obj381 = ClassWithMeta381()
obj381.show_meta_id()
```


```
class Meta382(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 382
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta382(metaclass=Meta382):
    def show_meta_id(self):
        return self.meta_id

obj382 = ClassWithMeta382()
obj382.show_meta_id()
```


```
class Meta383(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 383
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta383(metaclass=Meta383):
    def show_meta_id(self):
        return self.meta_id

obj383 = ClassWithMeta383()
obj383.show_meta_id()
```


```
class Meta384(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 384
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta384(metaclass=Meta384):
    def show_meta_id(self):
        return self.meta_id

obj384 = ClassWithMeta384()
obj384.show_meta_id()
```


```
class Meta385(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 385
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta385(metaclass=Meta385):
    def show_meta_id(self):
        return self.meta_id

obj385 = ClassWithMeta385()
obj385.show_meta_id()
```


```
class Meta386(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 386
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta386(metaclass=Meta386):
    def show_meta_id(self):
        return self.meta_id

obj386 = ClassWithMeta386()
obj386.show_meta_id()
```


```
class Meta387(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 387
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta387(metaclass=Meta387):
    def show_meta_id(self):
        return self.meta_id

obj387 = ClassWithMeta387()
obj387.show_meta_id()
```


```
class Meta388(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 388
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta388(metaclass=Meta388):
    def show_meta_id(self):
        return self.meta_id

obj388 = ClassWithMeta388()
obj388.show_meta_id()
```


```
class Meta389(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 389
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta389(metaclass=Meta389):
    def show_meta_id(self):
        return self.meta_id

obj389 = ClassWithMeta389()
obj389.show_meta_id()
```


```
class Meta390(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 390
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta390(metaclass=Meta390):
    def show_meta_id(self):
        return self.meta_id

obj390 = ClassWithMeta390()
obj390.show_meta_id()
```


```
class Meta391(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 391
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta391(metaclass=Meta391):
    def show_meta_id(self):
        return self.meta_id

obj391 = ClassWithMeta391()
obj391.show_meta_id()
```


```
class Meta392(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 392
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta392(metaclass=Meta392):
    def show_meta_id(self):
        return self.meta_id

obj392 = ClassWithMeta392()
obj392.show_meta_id()
```


```
class Meta393(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 393
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta393(metaclass=Meta393):
    def show_meta_id(self):
        return self.meta_id

obj393 = ClassWithMeta393()
obj393.show_meta_id()
```


```
class Meta394(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 394
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta394(metaclass=Meta394):
    def show_meta_id(self):
        return self.meta_id

obj394 = ClassWithMeta394()
obj394.show_meta_id()
```


```
class Meta395(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 395
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta395(metaclass=Meta395):
    def show_meta_id(self):
        return self.meta_id

obj395 = ClassWithMeta395()
obj395.show_meta_id()
```


```
class Meta396(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 396
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta396(metaclass=Meta396):
    def show_meta_id(self):
        return self.meta_id

obj396 = ClassWithMeta396()
obj396.show_meta_id()
```


```
class Meta397(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 397
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta397(metaclass=Meta397):
    def show_meta_id(self):
        return self.meta_id

obj397 = ClassWithMeta397()
obj397.show_meta_id()
```


```
class Meta398(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 398
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta398(metaclass=Meta398):
    def show_meta_id(self):
        return self.meta_id

obj398 = ClassWithMeta398()
obj398.show_meta_id()
```


```
class Meta399(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 399
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta399(metaclass=Meta399):
    def show_meta_id(self):
        return self.meta_id

obj399 = ClassWithMeta399()
obj399.show_meta_id()
```


```
class Meta400(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 400
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta400(metaclass=Meta400):
    def show_meta_id(self):
        return self.meta_id

obj400 = ClassWithMeta400()
obj400.show_meta_id()
```


```
class Meta401(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 401
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta401(metaclass=Meta401):
    def show_meta_id(self):
        return self.meta_id

obj401 = ClassWithMeta401()
obj401.show_meta_id()
```


```
class Meta402(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 402
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta402(metaclass=Meta402):
    def show_meta_id(self):
        return self.meta_id

obj402 = ClassWithMeta402()
obj402.show_meta_id()
```


```
class Meta403(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 403
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta403(metaclass=Meta403):
    def show_meta_id(self):
        return self.meta_id

obj403 = ClassWithMeta403()
obj403.show_meta_id()
```


```
class Meta404(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 404
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta404(metaclass=Meta404):
    def show_meta_id(self):
        return self.meta_id

obj404 = ClassWithMeta404()
obj404.show_meta_id()
```


```
class Meta405(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 405
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta405(metaclass=Meta405):
    def show_meta_id(self):
        return self.meta_id

obj405 = ClassWithMeta405()
obj405.show_meta_id()
```


```
class Meta406(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 406
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta406(metaclass=Meta406):
    def show_meta_id(self):
        return self.meta_id

obj406 = ClassWithMeta406()
obj406.show_meta_id()
```


```
class Meta407(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 407
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta407(metaclass=Meta407):
    def show_meta_id(self):
        return self.meta_id

obj407 = ClassWithMeta407()
obj407.show_meta_id()
```


```
class Meta408(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 408
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta408(metaclass=Meta408):
    def show_meta_id(self):
        return self.meta_id

obj408 = ClassWithMeta408()
obj408.show_meta_id()
```


```
class Meta409(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 409
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta409(metaclass=Meta409):
    def show_meta_id(self):
        return self.meta_id

obj409 = ClassWithMeta409()
obj409.show_meta_id()
```


```
class Meta410(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 410
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta410(metaclass=Meta410):
    def show_meta_id(self):
        return self.meta_id

obj410 = ClassWithMeta410()
obj410.show_meta_id()
```


```
class Meta411(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 411
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta411(metaclass=Meta411):
    def show_meta_id(self):
        return self.meta_id

obj411 = ClassWithMeta411()
obj411.show_meta_id()
```


```
class Meta412(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 412
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta412(metaclass=Meta412):
    def show_meta_id(self):
        return self.meta_id

obj412 = ClassWithMeta412()
obj412.show_meta_id()
```


```
class Meta413(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 413
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta413(metaclass=Meta413):
    def show_meta_id(self):
        return self.meta_id

obj413 = ClassWithMeta413()
obj413.show_meta_id()
```


```
class Meta414(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 414
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta414(metaclass=Meta414):
    def show_meta_id(self):
        return self.meta_id

obj414 = ClassWithMeta414()
obj414.show_meta_id()
```


```
class Meta415(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 415
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta415(metaclass=Meta415):
    def show_meta_id(self):
        return self.meta_id

obj415 = ClassWithMeta415()
obj415.show_meta_id()
```


```
class Meta416(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 416
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta416(metaclass=Meta416):
    def show_meta_id(self):
        return self.meta_id

obj416 = ClassWithMeta416()
obj416.show_meta_id()
```


```
class Meta417(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 417
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta417(metaclass=Meta417):
    def show_meta_id(self):
        return self.meta_id

obj417 = ClassWithMeta417()
obj417.show_meta_id()
```


```
class Meta418(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 418
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta418(metaclass=Meta418):
    def show_meta_id(self):
        return self.meta_id

obj418 = ClassWithMeta418()
obj418.show_meta_id()
```


```
class Meta419(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 419
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta419(metaclass=Meta419):
    def show_meta_id(self):
        return self.meta_id

obj419 = ClassWithMeta419()
obj419.show_meta_id()
```


```
class Meta420(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 420
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta420(metaclass=Meta420):
    def show_meta_id(self):
        return self.meta_id

obj420 = ClassWithMeta420()
obj420.show_meta_id()
```


```
class Meta421(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 421
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta421(metaclass=Meta421):
    def show_meta_id(self):
        return self.meta_id

obj421 = ClassWithMeta421()
obj421.show_meta_id()
```


```
class Meta422(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 422
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta422(metaclass=Meta422):
    def show_meta_id(self):
        return self.meta_id

obj422 = ClassWithMeta422()
obj422.show_meta_id()
```


```
class Meta423(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 423
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta423(metaclass=Meta423):
    def show_meta_id(self):
        return self.meta_id

obj423 = ClassWithMeta423()
obj423.show_meta_id()
```


```
class Meta424(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 424
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta424(metaclass=Meta424):
    def show_meta_id(self):
        return self.meta_id

obj424 = ClassWithMeta424()
obj424.show_meta_id()
```


```
class Meta425(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 425
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta425(metaclass=Meta425):
    def show_meta_id(self):
        return self.meta_id

obj425 = ClassWithMeta425()
obj425.show_meta_id()
```


```
class Meta426(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 426
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta426(metaclass=Meta426):
    def show_meta_id(self):
        return self.meta_id

obj426 = ClassWithMeta426()
obj426.show_meta_id()
```


```
class Meta427(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 427
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta427(metaclass=Meta427):
    def show_meta_id(self):
        return self.meta_id

obj427 = ClassWithMeta427()
obj427.show_meta_id()
```


```
class Meta428(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 428
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta428(metaclass=Meta428):
    def show_meta_id(self):
        return self.meta_id

obj428 = ClassWithMeta428()
obj428.show_meta_id()
```


```
class Meta429(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 429
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta429(metaclass=Meta429):
    def show_meta_id(self):
        return self.meta_id

obj429 = ClassWithMeta429()
obj429.show_meta_id()
```


```
class Meta430(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 430
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta430(metaclass=Meta430):
    def show_meta_id(self):
        return self.meta_id

obj430 = ClassWithMeta430()
obj430.show_meta_id()
```


```
class Meta431(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 431
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta431(metaclass=Meta431):
    def show_meta_id(self):
        return self.meta_id

obj431 = ClassWithMeta431()
obj431.show_meta_id()
```


```
class Meta432(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 432
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta432(metaclass=Meta432):
    def show_meta_id(self):
        return self.meta_id

obj432 = ClassWithMeta432()
obj432.show_meta_id()
```


```
class Meta433(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 433
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta433(metaclass=Meta433):
    def show_meta_id(self):
        return self.meta_id

obj433 = ClassWithMeta433()
obj433.show_meta_id()
```


```
class Meta434(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 434
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta434(metaclass=Meta434):
    def show_meta_id(self):
        return self.meta_id

obj434 = ClassWithMeta434()
obj434.show_meta_id()
```


```
class Meta435(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 435
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta435(metaclass=Meta435):
    def show_meta_id(self):
        return self.meta_id

obj435 = ClassWithMeta435()
obj435.show_meta_id()
```


```
class Meta436(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 436
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta436(metaclass=Meta436):
    def show_meta_id(self):
        return self.meta_id

obj436 = ClassWithMeta436()
obj436.show_meta_id()
```


```
class Meta437(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 437
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta437(metaclass=Meta437):
    def show_meta_id(self):
        return self.meta_id

obj437 = ClassWithMeta437()
obj437.show_meta_id()
```


```
class Meta438(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 438
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta438(metaclass=Meta438):
    def show_meta_id(self):
        return self.meta_id

obj438 = ClassWithMeta438()
obj438.show_meta_id()
```


```
class Meta439(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 439
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta439(metaclass=Meta439):
    def show_meta_id(self):
        return self.meta_id

obj439 = ClassWithMeta439()
obj439.show_meta_id()
```


```
class Meta440(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 440
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta440(metaclass=Meta440):
    def show_meta_id(self):
        return self.meta_id

obj440 = ClassWithMeta440()
obj440.show_meta_id()
```


```
class Meta441(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 441
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta441(metaclass=Meta441):
    def show_meta_id(self):
        return self.meta_id

obj441 = ClassWithMeta441()
obj441.show_meta_id()
```


```
class Meta442(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 442
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta442(metaclass=Meta442):
    def show_meta_id(self):
        return self.meta_id

obj442 = ClassWithMeta442()
obj442.show_meta_id()
```


```
class Meta443(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 443
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta443(metaclass=Meta443):
    def show_meta_id(self):
        return self.meta_id

obj443 = ClassWithMeta443()
obj443.show_meta_id()
```


```
class Meta444(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 444
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta444(metaclass=Meta444):
    def show_meta_id(self):
        return self.meta_id

obj444 = ClassWithMeta444()
obj444.show_meta_id()
```


```
class Meta445(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 445
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta445(metaclass=Meta445):
    def show_meta_id(self):
        return self.meta_id

obj445 = ClassWithMeta445()
obj445.show_meta_id()
```


```
class Meta446(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 446
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta446(metaclass=Meta446):
    def show_meta_id(self):
        return self.meta_id

obj446 = ClassWithMeta446()
obj446.show_meta_id()
```


```
class Meta447(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 447
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta447(metaclass=Meta447):
    def show_meta_id(self):
        return self.meta_id

obj447 = ClassWithMeta447()
obj447.show_meta_id()
```


```
class Meta448(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 448
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta448(metaclass=Meta448):
    def show_meta_id(self):
        return self.meta_id

obj448 = ClassWithMeta448()
obj448.show_meta_id()
```


```
class Meta449(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 449
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta449(metaclass=Meta449):
    def show_meta_id(self):
        return self.meta_id

obj449 = ClassWithMeta449()
obj449.show_meta_id()
```


```
class Meta450(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 450
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta450(metaclass=Meta450):
    def show_meta_id(self):
        return self.meta_id

obj450 = ClassWithMeta450()
obj450.show_meta_id()
```


```
class Meta451(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 451
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta451(metaclass=Meta451):
    def show_meta_id(self):
        return self.meta_id

obj451 = ClassWithMeta451()
obj451.show_meta_id()
```


```
class Meta452(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 452
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta452(metaclass=Meta452):
    def show_meta_id(self):
        return self.meta_id

obj452 = ClassWithMeta452()
obj452.show_meta_id()
```


```
class Meta453(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 453
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta453(metaclass=Meta453):
    def show_meta_id(self):
        return self.meta_id

obj453 = ClassWithMeta453()
obj453.show_meta_id()
```


```
class Meta454(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 454
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta454(metaclass=Meta454):
    def show_meta_id(self):
        return self.meta_id

obj454 = ClassWithMeta454()
obj454.show_meta_id()
```


```
class Meta455(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 455
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta455(metaclass=Meta455):
    def show_meta_id(self):
        return self.meta_id

obj455 = ClassWithMeta455()
obj455.show_meta_id()
```


```
class Meta456(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 456
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta456(metaclass=Meta456):
    def show_meta_id(self):
        return self.meta_id

obj456 = ClassWithMeta456()
obj456.show_meta_id()
```


```
class Meta457(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 457
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta457(metaclass=Meta457):
    def show_meta_id(self):
        return self.meta_id

obj457 = ClassWithMeta457()
obj457.show_meta_id()
```


```
class Meta458(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 458
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta458(metaclass=Meta458):
    def show_meta_id(self):
        return self.meta_id

obj458 = ClassWithMeta458()
obj458.show_meta_id()
```


```
class Meta459(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 459
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta459(metaclass=Meta459):
    def show_meta_id(self):
        return self.meta_id

obj459 = ClassWithMeta459()
obj459.show_meta_id()
```


```
class Meta460(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 460
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta460(metaclass=Meta460):
    def show_meta_id(self):
        return self.meta_id

obj460 = ClassWithMeta460()
obj460.show_meta_id()
```


```
class Meta461(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 461
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta461(metaclass=Meta461):
    def show_meta_id(self):
        return self.meta_id

obj461 = ClassWithMeta461()
obj461.show_meta_id()
```


```
class Meta462(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 462
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta462(metaclass=Meta462):
    def show_meta_id(self):
        return self.meta_id

obj462 = ClassWithMeta462()
obj462.show_meta_id()
```


```
class Meta463(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 463
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta463(metaclass=Meta463):
    def show_meta_id(self):
        return self.meta_id

obj463 = ClassWithMeta463()
obj463.show_meta_id()
```


```
class Meta464(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 464
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta464(metaclass=Meta464):
    def show_meta_id(self):
        return self.meta_id

obj464 = ClassWithMeta464()
obj464.show_meta_id()
```


```
class Meta465(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 465
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta465(metaclass=Meta465):
    def show_meta_id(self):
        return self.meta_id

obj465 = ClassWithMeta465()
obj465.show_meta_id()
```


```
class Meta466(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 466
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta466(metaclass=Meta466):
    def show_meta_id(self):
        return self.meta_id

obj466 = ClassWithMeta466()
obj466.show_meta_id()
```


```
class Meta467(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 467
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta467(metaclass=Meta467):
    def show_meta_id(self):
        return self.meta_id

obj467 = ClassWithMeta467()
obj467.show_meta_id()
```


```
class Meta468(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 468
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta468(metaclass=Meta468):
    def show_meta_id(self):
        return self.meta_id

obj468 = ClassWithMeta468()
obj468.show_meta_id()
```


```
class Meta469(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 469
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta469(metaclass=Meta469):
    def show_meta_id(self):
        return self.meta_id

obj469 = ClassWithMeta469()
obj469.show_meta_id()
```


```
class Meta470(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 470
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta470(metaclass=Meta470):
    def show_meta_id(self):
        return self.meta_id

obj470 = ClassWithMeta470()
obj470.show_meta_id()
```


```
class Meta471(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 471
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta471(metaclass=Meta471):
    def show_meta_id(self):
        return self.meta_id

obj471 = ClassWithMeta471()
obj471.show_meta_id()
```


```
class Meta472(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 472
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta472(metaclass=Meta472):
    def show_meta_id(self):
        return self.meta_id

obj472 = ClassWithMeta472()
obj472.show_meta_id()
```


```
class Meta473(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 473
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta473(metaclass=Meta473):
    def show_meta_id(self):
        return self.meta_id

obj473 = ClassWithMeta473()
obj473.show_meta_id()
```


```
class Meta474(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 474
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta474(metaclass=Meta474):
    def show_meta_id(self):
        return self.meta_id

obj474 = ClassWithMeta474()
obj474.show_meta_id()
```


```
class Meta475(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 475
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta475(metaclass=Meta475):
    def show_meta_id(self):
        return self.meta_id

obj475 = ClassWithMeta475()
obj475.show_meta_id()
```


```
class Meta476(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 476
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta476(metaclass=Meta476):
    def show_meta_id(self):
        return self.meta_id

obj476 = ClassWithMeta476()
obj476.show_meta_id()
```


```
class Meta477(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 477
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta477(metaclass=Meta477):
    def show_meta_id(self):
        return self.meta_id

obj477 = ClassWithMeta477()
obj477.show_meta_id()
```


```
class Meta478(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 478
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta478(metaclass=Meta478):
    def show_meta_id(self):
        return self.meta_id

obj478 = ClassWithMeta478()
obj478.show_meta_id()
```


```
class Meta479(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 479
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta479(metaclass=Meta479):
    def show_meta_id(self):
        return self.meta_id

obj479 = ClassWithMeta479()
obj479.show_meta_id()
```


```
class Meta480(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 480
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta480(metaclass=Meta480):
    def show_meta_id(self):
        return self.meta_id

obj480 = ClassWithMeta480()
obj480.show_meta_id()
```


```
class Meta481(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 481
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta481(metaclass=Meta481):
    def show_meta_id(self):
        return self.meta_id

obj481 = ClassWithMeta481()
obj481.show_meta_id()
```


```
class Meta482(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 482
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta482(metaclass=Meta482):
    def show_meta_id(self):
        return self.meta_id

obj482 = ClassWithMeta482()
obj482.show_meta_id()
```


```
class Meta483(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 483
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta483(metaclass=Meta483):
    def show_meta_id(self):
        return self.meta_id

obj483 = ClassWithMeta483()
obj483.show_meta_id()
```


```
class Meta484(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 484
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta484(metaclass=Meta484):
    def show_meta_id(self):
        return self.meta_id

obj484 = ClassWithMeta484()
obj484.show_meta_id()
```


```
class Meta485(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 485
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta485(metaclass=Meta485):
    def show_meta_id(self):
        return self.meta_id

obj485 = ClassWithMeta485()
obj485.show_meta_id()
```


```
class Meta486(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 486
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta486(metaclass=Meta486):
    def show_meta_id(self):
        return self.meta_id

obj486 = ClassWithMeta486()
obj486.show_meta_id()
```


```
class Meta487(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 487
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta487(metaclass=Meta487):
    def show_meta_id(self):
        return self.meta_id

obj487 = ClassWithMeta487()
obj487.show_meta_id()
```


```
class Meta488(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 488
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta488(metaclass=Meta488):
    def show_meta_id(self):
        return self.meta_id

obj488 = ClassWithMeta488()
obj488.show_meta_id()
```


```
class Meta489(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 489
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta489(metaclass=Meta489):
    def show_meta_id(self):
        return self.meta_id

obj489 = ClassWithMeta489()
obj489.show_meta_id()
```


```
class Meta490(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 490
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta490(metaclass=Meta490):
    def show_meta_id(self):
        return self.meta_id

obj490 = ClassWithMeta490()
obj490.show_meta_id()
```


```
class Meta491(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 491
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta491(metaclass=Meta491):
    def show_meta_id(self):
        return self.meta_id

obj491 = ClassWithMeta491()
obj491.show_meta_id()
```


```
class Meta492(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 492
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta492(metaclass=Meta492):
    def show_meta_id(self):
        return self.meta_id

obj492 = ClassWithMeta492()
obj492.show_meta_id()
```


```
class Meta493(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 493
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta493(metaclass=Meta493):
    def show_meta_id(self):
        return self.meta_id

obj493 = ClassWithMeta493()
obj493.show_meta_id()
```


```
class Meta494(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 494
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta494(metaclass=Meta494):
    def show_meta_id(self):
        return self.meta_id

obj494 = ClassWithMeta494()
obj494.show_meta_id()
```


```
class Meta495(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 495
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta495(metaclass=Meta495):
    def show_meta_id(self):
        return self.meta_id

obj495 = ClassWithMeta495()
obj495.show_meta_id()
```


```
class Meta496(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 496
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta496(metaclass=Meta496):
    def show_meta_id(self):
        return self.meta_id

obj496 = ClassWithMeta496()
obj496.show_meta_id()
```


```
class Meta497(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 497
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta497(metaclass=Meta497):
    def show_meta_id(self):
        return self.meta_id

obj497 = ClassWithMeta497()
obj497.show_meta_id()
```


```
class Meta498(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 498
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta498(metaclass=Meta498):
    def show_meta_id(self):
        return self.meta_id

obj498 = ClassWithMeta498()
obj498.show_meta_id()
```


```
class Meta499(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 499
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta499(metaclass=Meta499):
    def show_meta_id(self):
        return self.meta_id

obj499 = ClassWithMeta499()
obj499.show_meta_id()
```


```
class Meta500(type):
    def __new__(cls, name, bases, dct):
        dct['meta_id'] = 500
        return super().__new__(cls, name, bases, dct)

class ClassWithMeta500(metaclass=Meta500):
    def show_meta_id(self):
        return self.meta_id

obj500 = ClassWithMeta500()
obj500.show_meta_id()
```


---
**Score: 500**