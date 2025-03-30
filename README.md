class loanApproval
{
	double salary;
	public String booleanisEligible(double salary)
	{
		if(salary>=50000)
		{
		return "true";
		}
		else
		{
		return "false";
		}
	}
	public static void main(String []args)
	{
	loanApproval app=new loanApproval();
	
	app.salary=15500l;
	
	String result=app.booleanisEligible(app.salary);
	
	System.out.println(result);	
	}

}

	
