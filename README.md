# library-mamagement-system-using-python#creat library class
#1display book
#2landbook
#3add book
#return book
class Library:
    def __init__(self,list,name):
        self.booklist=list
        self.name=name
        self.landdict={}
    def displaybook(self):
        print("we have the following book in library:(self.name)")
        for book in self .booklist:
            print(book)
    def landbook(self,user,book):
        if book not in self.landdict.key():
            self.landdict.update({book.user})
            print("lander book has been update.you can take the book now")
        else:
            print("book is already being used by {self.landdict[]}")
    def addbook(self,book):
        self.booklist.append(book)
        print("book has been added to the list")
    def Returnbook(self, book):
        self.booklist.remove(book)
if __name__=='__main__':
    rakesh=Library(['python','datastructure','compiler deining','objected oriented','c++'],"rakeh")
    
    while(True):
        print("welcome to {rakesh.library}library""enter your choice")
        print("1. display book")
        print("2. land book")
        print("3. add book")
        print("4. Return book")
        user_choice=str(input())
        if user_choice=='1':
            rakesh.displaybook()
        elif user_choice=='2':
            book=input("enter the name of the book")
            name=input("enter your name")
            rakesh,landbook()
        elif user_choice=='3':
            book=input("enter the name of the book you want to add")
            rakesh.addbook
        elif user_choice=='4':
            book=input("enter the book you want to Return")
            rakesh.Returnbook
        else:
            print("not valid option ")
            print("press Q for quite and C to continue")
            user_choice2== ' '
            while(user_choice2=="C" and user_choice2=="Q"):
                if a=="Q":
                    exit
                elif user_choice2=="C":
                    continue
