# JavaSimplePrgm
Some simple programs

public class patterns {

	public static void main(String[] args) {
		
		int n=5;
		for(int row=1;row<=n;row++)
		{
			for(int col=1;col<=n;col++)
				
			{
				if(row<=col)
				{
				System.out.print("*");
				}else
				{
					System.out.print("");
				}
		}
			System.out.println();
	}
		// right angle
		for(int row=1;row<=n;row++)
		{
			for(int col=1;col<=n;col++)
				
			{
				if(row>=col)
				{
					System.out.print("*");
				}else
				{
					System.out.print(" ");
				}
			}
				for(int col=n;col>=1;col--){
				if(row>=col){
					System.out.print("*");
				}else{
					System.out.print(" ");
				}
			}
			System.out.println();
		}
		
		
		for(int row=1;row<=n;row++)
			{
				for(int col=n;col>=1;col--)
					
				{
					if(row<=col)
					{
						System.out.print("*");
					}else
					{
						System.out.print(" ");
					}
				}
				
				System.out.println();
			}
		for(int row=1;row<=n;row++)
			{
				for(int col=1;col<=n;col++)
					
				{
					if(row>=col)
					{
						System.out.print("*");
					}else
					{
						System.out.print(" ");
					}
					
				}
				System.out.println();
				}
		for(int row=1;row<=n;row++)
		{
			for(int col=n;col>=1;col--)
				
			{
				if(row<=col)
				{
					System.out.print("*");
				}else
				{
					System.out.print(" ");
				}
			}
			for(int col=1;col<=n;col++)
				
			{
				if(row<=col)
				{
					System.out.print("*");
				}else
				{
					System.out.print(" ");
				}
			}
			
			System.out.println();
		}
		
		
		for(int row=1;row<=n;row++)
		{
				for(int col=1;col<=n;col++)
					
			{
					if(row<=col)
					{
						System.out.print("*");
					}else
				{
					System.out.print(" ");
					}
				}
				
				System.out.println();
			}
		for(int row=1;row<=n;row++)
			{
				for(int col=n;col>=1;col--)
					
				{
				if(row>=col)
					{
						System.out.print("*");
					}else
					{
						System.out.print(" ");
				}
					
				}
				System.out.println();
				}
		
		for(int row=1;row<=n;row++)
			{
			for(int col=1;col<=n;col++)
					
				{
				if(row<=col)
					{
						System.out.print("* ");
					}else					{
						System.out.print(" ");
					}
				}
				
				System.out.println();
			}
		for(int row=1;row<=n;row++)
			{
				for(int col=n;col>=1;col--)
					
				{
					if(row>=col)
					{
						System.out.print("* ");
					}else
					{
						System.out.print(" ");
					}
					
				}
				System.out.println();
				}
		for(int row=1;row<=n;row++)
			{
				for(int col=n;col>=1;col--)
					
				{
					if(row>=col)
					{
						System.out.print("* ");
					}else
					{
						System.out.print(" ");
					}
				}
				
				System.out.println();
			}
		for(int row=1;row<=n;row++)
			{
				for(int col=1;col<=n;col++)
					
				{
					if(row<=col)
					{
						System.out.print("* ");
					}else
					{
						System.out.print(" ");
					}
					
				}
				System.out.println();
				}
		}
	
	}

