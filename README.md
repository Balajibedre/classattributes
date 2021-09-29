# classattributes

class Employee:
  def_init_(self,name,salary):
    self.name = name
    self.salary = salary
  def info(self):
    print(f"Name:{self.name}")
    print(f"salary:{self.salary}")
emp = Employee("Python.hub","/million")
emp.info()
print(emp._dict_)
print(emp._doc_)
print(emp._module_)
print(emp._class_)
  
