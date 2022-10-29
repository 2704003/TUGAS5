# TUGAS5
TUGAS5
public class Person{

    private String nama;
    private String jenisKelamin;
    private int umur;

    public void setNama(String nama){
        this.nama = nama;
    }
    public void setJenisKelamin(String gender){
        this.jenisKelamin = gender;
    }
    public void setUmur(int umur) {
        this.umur = umur;
    }


    public String getNama() {
        return this.nama;
    }
    public String getJenisKelamin(){
        return this.jenisKelamin;
    }
    public int getUmur() {
        return this.umur;
    }
}

class Object{
    public static void main(String[] args) {
       Person person1 = new Person();
       Person person2 = new Person();

        person1.setNama("Anton");
        person1.setJenisKelamin("Pria");
        person1.setUmur(20);
        person2.setNama("Riko");
        person2.setJenisKelamin("Pria");
        person2.setUmur(22);

        System.out.println("Biodata :");
        System.out.println("1. Nama   = " +person1.getNama());
        System.out.println("   Gender = " +person1.getJenisKelamin());
        System.out.println("   Usia   = " +person1.getUmur() + " Tahun \n");
        System.out.println("2. Nama   = " +person2.getNama());
        System.out.println("   Gender = " +person2.getJenisKelamin());
        System.out.println("   Usia   = " +person2.getUmur() + " Tahun");
    }

}
