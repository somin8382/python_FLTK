from fltk import* # import fltk
#w=Fl_Window(0,500,600,300,'hihi') #x,y, w,h ,text  fltk.Fl_Window
w=Fl_Window(Fl.w()/2-300,Fl.h()/2-150,600,300,'hihi')
w.label('this is my label')

w.begin() # optional. all created widgets will be added to w
b1=Fl_Button(0,0,70,40,"OK")
b2=Fl_Button(530,0,70,40,"OK")
b3=Fl_Button(530,260,70,40,"OK")  #x,y, w,h ,text
b4=Fl_Button(0,260,70,40,"OK")
b5=Fl_Button(300-35,150-20,70,40,"OK")

#b5=Fl_Button(Fl_Window.h()/2,Fl_Window.w()/2,70,40,"OK")
#b5=Fl_Button(Fl.h(),Fl.w()/2,70,40,"OK")
#b5=Fl_Button(300,600,70,40,"OK")
#b5=Fl_Button(512,640,70,40,"OK")
w.end()

w.show()
Fl.run()

#firefox/home/inter/documentation/index.html
