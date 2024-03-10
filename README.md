
#include <iostream>
#include <windows.h>
#include <ctime>
#include <conio.h>

const int width = 60;
const int height = 40;
const int dw = 10;
const int dh = 5;

void gotoxy(int x, int y) {
	COORD coord;
	coord.X = x;
	coord.Y = y;
	SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE), coord);
}

void dibujar(char plano[height][width], int x, int y, char symbol) {
	plano[y][x] = symbol;
}

char obs[1][2][8] = {
	{"=U=    ", "=B=    "}
};

struct coord {
	int a;
	int z;
};

struct dato {
	coord pos[14];
	char car[14];
};

dato pass[12];
dato choqueR[1];
dato choquec[12][5];
class Mapa {
private:
	int z, w, v, p;
	
	int gu1,gu2,gu3,gu4,ac=0;
	
	int s,con=8,con1=0;
	int min=300;
	float vy = 0.0f;
	int dir = 0;
	
	int py[10] = {1, 2, 3, 4, 5, 7, 8, 9, 10, 11};
	
	int sb[13] = {0, 3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 33, 36};
	int nc[12] = {6, 6, 6, 6, 9, 5, 7, 14, 10, 6, 6, 6};
	int pc[10] = {2, 1, 3, 1, 4, 11, 9, 8, 10, 7};
	int GR[12] = {5, 5, 4, 4, 3, 3, 2, 2, 1, 1, 1, 1};
	
	int AL [5];
	
	
	
	int niveles[12][10] = {
		{3, 2, 3, 1, 2, 4, 3, 4, 3},
	{4, 3, 3, 1, 3, 3, 3, 1, 4, 3},
		{4, 4, 3, 2, 3, 3, 3, 1, 4, 1},
	{4, 4, 4, 3, 3, 2, 2, 1, 3, 1},
		{4, 4, 4, 3, 3, 2, 2, 1, 3, 1},
	{4, 4, 4, 3, 3, 2, 2, 1, 3, 1},
		{4, 4, 4, 3, 3, 2, 2, 1, 3, 1},
	{4, 4, 4, 3, 3, 2, 2, 1, 3, 1},
		{4, 4, 4, 3, 3, 2, 2, 1, 3, 1},
	{4, 4, 4, 3, 3, 2, 2, 1, 3, 1},
		{4, 4, 4, 3, 3, 2, 2, 1, 3, 1},
	{4, 4, 4, 3, 3, 2, 1, 3, 1},
	};
	int lin[4][4] = {
		{23, 1, 1, 1},
	{17, 46, 1, 1},
		{6, 26, 45, 1},
	{2, 16, 30, 44},
	};
	int i;  // Declare i
	// Mapa.h
	class nivel {
	public:
		int getI() const;  // Declaración de la función getter
	private:
		int i;
	};
	// Assuming Mapa class definition with member variable 'i'
	class Mapa {
	public:
		Mapa(); // Constructor declaration
		// Other member functions and variables
	};
	
		int getI() const {
			return i;
		}
		
	private:
			int i; // Placeholder for the member variable 'i'
	};
	
	// Usage in sin_titulo.cpp
	int main() {
		// Assuming 'someObject' is an instance of the Mapa class
		Mapa someObject;
		
		// Reemplaza la línea 84 con algo como:
		int valorI = someObject.getI();
		
		coord car[12][5];
		
		// Assuming 'i' is declared and initialized
		int i = 10; // Placeholder for the actual value of 'i'
		coord car1[i];
		
		// Some code...
		
		// ... code ...
		
		// Ensure balanced braces
		// ... more code ...
		
		
	
	// int main() {
		// Assuming 'someObject' is an instance of the Mapa class
		
public:
	int retz() {
		return z;
	}
	
	int retw() {
		return w;
	}
	
	Mapa(int z1, int w1, int v1, int p1) {
		z = z1;
		w = w1;
		v = v1;
		p = p1;
	}
	
	void pmap(char plano[height][width]) {
		for (int i = 0; i < width; i++) {
			for (int y = 0; y < height; y++) {
				if (i == 0 || i == width - 1 || y == 0 || y == height - 1) {
					dibujar(plano, i, y, '\'');
				} else if (i % 3 == 0) {
					dibujar(plano, i, y, '_');
				}
			}
		}
	}
	
	void pasar() {
		for (int b = 0; b < 1; b++) {
			int y = 0;
			for (int i = 0; i < 2; i++) {
				y = 2 - i;
			}
			
			int i = 0;
			for (int f = 0; f < 7; f++) {
				if (strcmp(obs[b][i], "    ") != 0) {
					pass[b].pos[i] = {f, y};
					pass[b].car[i] = obs[b][i][f];
					i++;
				}
			}
		}
	}
	
	
}	
		 
			// Your existing code here
	
// Some code...

	// ... code ...
} // <-- Ensure there is no misplaced code after this brace

		
		// loop body


dibujar(plano, pass[c].pos[i].a, pass[c].pos[i].z, pass[c].car[i]);
choqueR[0].pos[i].x = (x+pass[c].pos[i].x); 		
choqueR[0].pos[i].y = (SB [Y]+pass[c].pos[i].y);

};

}
};
//funcion que crea los automoviles
void draw(char plano[height/Dh][width/dw+1], int t, int u , int c, dato choquec)
	
	
	
}
for (int j = 0; j < t; j++).
	
	
}
for (int i=0;i<NC[c];i++)
	
}

dibujar(plano,(cat[u][j].x)+pass[c].poa[i].x ,(SB(car[u][j].]+pass[c].pos[i].y
	choqueC[u][j].pos[i].x =  (car[u][j].x)+pass[c].pos[i],x;
	choqueC[u][j].pos[i].y =  (SB[car[u][j].y)+pass[c].pos[i],y;
	
	
	
	
	void generacion(char plano[height / dh][width / dw + 1], int nivel,dato choque[12]) {
		{
		draw(plano,,GR[nivel],10,PC[6],choque);
		for (int i=0;i<10;i++) {
			draw(plano,niveles[nivel][i],i,pc[i],choque);
		}
		
	}
	
	void dir2() {
		if (vy <= 600.0f)
			vy = 800.0f;
	}
	
	void mostrar()
	{
		
	}
	void des()
	{   
		p1++;
		if(p1>10)
			p1=0;
		
		p2++;
		if(p2>15)
			p21=0;
		
		p3++;
		if(p3>20)
			p3=0;
		
		
		p4++;
		if(p4>30)
		{
			p4=0;
			min--;
		}	
	
