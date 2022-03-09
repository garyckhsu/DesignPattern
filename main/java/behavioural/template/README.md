# 在模板方法中會呼叫多個定義在父類別的其他方法，而這些方法有可能只是抽象方法並沒有實作，模板方法僅決定這些抽象方法的執行順序，這些抽象方法的實作由子類別負責，並且子類別不允許覆寫模板方法

父類別會定義一個final function，裡面會循序呼叫定義子類別用到的介面，子類別依照父類別定義的介面實作。



![img.png](img.png)