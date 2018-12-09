# study
jp.kyoto.kita.java

package ql;

public class study {
	public static void main(String[] args)
	{
		System.out.println("nihao fool");
		
		student a = new student("aa");
		//a.setName("aa");
		System.out.println(a.getName());
		a.exshow();
		a.exThreeShow();//a継承したので直接引用など大丈夫です以上　Githuｂの内容
		
		
	}

}


class student extends BollpointPen
{
	private String name;
	private String age;
	
	student(String name)
	{
		this.name = name;
		this.age = age;
		
	}

	public String getName() {
		return name;
	}

	public void setName(String name) {
		this.name = name;
	}
	
	void exThreeShow()
	{
		System.out.println("これは、三色ボールペンクラスです。");
	}
}

class BollpointPen
{
	void exshow()//void メッソド　値返すなし
	{
		System.out.println("これは、ボールペンクラスです。");
	}
}
