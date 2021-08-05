package sistemascoordenadas2d;

public class SistemasCoordenadas2D {

	public static void main(String[] args) {
	
		Cartesiana2D punto = new Cartesiana2D();
		Polar punto2 = new Polar();
		Cartesiana2D punto3 = new Cartesiana2D(punto2);
		
		punto.setX(4);

	}

}

class Cartesiana2D {
	
	private int x, y;

	public void setX(int x) {
		this.x = x;
	}

	public void setY(int y) {
		this.y = y;
	}
		
}

class Polar{
	
	private int radio;
	private float angulo;
	
	public int getRadio() {
		return radio;
	}
	public float getAngulo() {
		return angulo;
	}
	public void setRadio(int radio) {
		this.radio = radio;
	}
	public void setAngulo(float angulo) {
		this.angulo = angulo;
	}
	
	
}