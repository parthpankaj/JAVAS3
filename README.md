# JAVAS3
public class Test {
	static{
		print(10);  // compiler error if i put println same only.
	}
	static void println(int x)
	{
		System.out.println(x);
		System.exit(0);
}
}




***output***
compiler error
