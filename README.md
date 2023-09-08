public class Reserva {
 
	private String nombre;
	private String hora;
	private int comensales;
	private String telefono;
 
	public Reserva(String nombre, String hora, int comensales, String telefono) {
		this.nombre = nombre;
		this.hora = hora;
		this.comensales = comensales;
		this.telefono = telefono;
	}
 
	public String getNombre() {
		return nombre;
	}
 
	public void setNombre(String nombre) {
		this.nombre = nombre;
	}
 
	public String getHora() {
		return hora;
	}
 
	public void setHora(String hora) {
		this.hora = hora;
	}
 
	public int getComensales() {
		return comensales;
	}
 
	public void setComensales(int comensales) {
		this.comensales = comensales;
	}
 
	public String getTelefono() {
		return telefono;
	}
 
	public void setTelefono(String telefono) {
		this.telefono = telefono;
	}
 
}
