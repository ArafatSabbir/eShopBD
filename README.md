# eShopBD
E-Commerce application ( EShopBD ) using ASP.NET Core 3.1, MSSQL Server, Repository Pattern, N-Tier Architecture, API's, EF
Core and Bootstrap 4.

## Architecture
*Languages*: C#, HTML, CSS, JavaScript <br />
*Tools*: Visual Studion 2019, MSSQL Server Management Studio, Bootstrap 4<br />
*Type of Application*: Web Application <br />

## Project Directory
<br />
<pre> 
	eShopBD[Solution]
		|
		|
		|------eShopBD
		|	
		|
		|------eShopBD.DataAccess
    |	
		|
		|------eShopBD.Models
    |	
		|
		|------eShopBD.Utility
				
</pre>

<h3> Edit database connection string in appsettings.json </h3>
<code> 
	"DefaultConnection": "server=localhost;userid=root;pwd=[database password];port=[your port number];
	database=ExamService;sslmode=none;charset=utf8;" 
</code>
<br /> <b> Example :</b> <br />
<code> 
	"DefaultConnection": "server=localhost;userid=root;pwd=;port=3306;
	database=ExamService;sslmode=none;charset=utf8;" 
</code>

## How to Setting, Build and Run
The following is required to run the program.
1. Open Visual Studio 2019 Community or Enterprise edition.
2. Open MSSQL Server Management Studio.
3. Set database connection string.
4. Update DataBase and Hit IIS Express.

**ENJOY!**
