(differentials)=
# Дифференциалы

Когда я пишу рубленый $\frac{d}{dx}$ это **полный дифференциал**, он отыскивает все упоминания о $x$ в выражении и суммирует все связанные с ними частные производные и дифференциирует дальше вглубь. Когда я пишу курсивный $\frac{\partial}{\partial x}$ это **частная производная**, она дифференциирует функцию по аргументу, не по значению аргумента. 

Почуствуйте разницу:

$$ f(x,y) = sin x + y \quad \Rightarrow \quad \frac{\partial}{\partial x} f(x, x^2) = \cos x, \quad \frac{d}{d x} f(x, x^2) = \cos x + 2x$$

Не во всех учебниках делается различие, потому что из контекста обычно понятно, частная производная берется или полный дифференциал.