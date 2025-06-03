# 授業まとめ
class MyHomepage extends statefulwidget
 MyHomepage({key key}):super({key key});@override
 MyHomepageStart createState()=> new_MyHomePageState();
 class_MyHomePageState extends state<MyHomePage>
  @override
  widget build(BuildContext context)
   return new Scaffold
   appBar:new AppBar
    title:new Text(`App Name`),
