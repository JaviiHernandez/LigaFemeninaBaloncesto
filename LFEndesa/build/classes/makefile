all:
	javac -cp ../dist/lib/biblioteca.jar lfendesa/LFEndesa.java view/View.java controller/Controller.java model/LigaFem.java model/Jugadora.java model/Jornada.java model/Equipo.java model/Datos_equipo.java model/Partido.java
	jar cvmf manifest LFEndesa.jar ../dist/lib/biblioteca.jar lfendesa/LFEndesa.class view/View.class controller/Controller.class model/LigaFem.class model/Jugadora.class model/Jornada.class model/Equipo.class model/Datos_equipo.class model/Partido.class
	
clean:
	rm *.class

