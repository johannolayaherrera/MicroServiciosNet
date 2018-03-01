# MicroServiciosNet


Libro
https://inspirit.net.in/books/placements/Cracking%20the%20Coding%20Interview.pdf
------------------------------

Prueba y lecciones en codility y pruebas	
https://app.codility.com/programmers/challenges/
https://blog.codility.com/2011/03/solutions-for-task-equi.html
https://www.testdome.com/tests/c-sharp-net-online-test/67
http://bigocheatsheet.com/




https://blogs.msdn.microsoft.com/cesardelatorre/2017/05/10/free-ebookguide-on-net-microservices-architecture-for-containerized-net-applications/


https://stackskills.com/p/clean-code
https://www.codeproject.com/Articles/539179/Some-practices-to-write-better-Csharp-NET-code
https://www.codeproject.com/Articles/1083348/Csharp-BAD-PRACTICES-Learn-how-to-make-a-good-code
https://code.tutsplus.com/tutorials/top-15-best-practices-for-writing-super-readable-code--net-8118
http://www.c-sharpcorner.com/article/important-tips-to-write-clean-code-in-visual-studio/
https://www.pluralsight.com/guides/microsoft-net/tips-for-writing-better-c-code
http://cvuorinen.net/2014/04/what-is-clean-code-and-why-should-you-care/
https://stackoverflow.com/questions/2720480/how-to-write-clean-code-in-c-sharp-language-and-improve-quality-of-code
https://msdn.microsoft.com/en-us/magazine/dn802600.aspx
https://www.makeuseof.com/tag/10-tips-writing-cleaner-better-code/
https://gooroo.io/GoorooTHINK/Article/17142/Tips-for-writing-clean-and-best-code-in-C/26389#.WpWa1GnOXcs
http://businessinteriorsidaho.com/wp-content/uploads/2016/09/DotNetCodingStandard.pdf
https://www.developerhandbook.com/c-sharp/how-to-write-more-efficient-and-maintainable-csharp-code/
http://www.informit.com/articles/article.aspx?p=2223710
https://blog.goyello.com/2013/01/21/top-9-principles-clean-code/
https://stackskills.com/p/clean-code
https://stackoverflow.com/questions/1490385/good-quality-c-sharp-code
https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/inside-a-program/coding-conventions
https://spin.atomicobject.com/2015/12/15/c-sharp-code-quality/
https://itplamen.wordpress.com/category/c-high-quality-programming-code/
https://simpleprogrammer.com/5-tips-code-quality/
http://www.introprogramming.info/english-intro-csharp-book/read-online/chapter-21-high-quality-programming-code/
https://programmingwithmosh.com/csharp/5-tips-for-junior-c-developers-to-write-cleaner-c-code/
https://softwareengineering.stackexchange.com/questions/65705/how-to-code-faster-without-sacrificing-quality
https://improvingsoftware.com/2011/06/27/5-best-practices-for-commenting-your-code/
https://www.toptal.com/qa/how-to-write-testable-code-and-why-it-matters
http://www.garshol.priv.no/blog/105.html
http://www.dotnetcurry.com/patterns-practices/1358/code-quality-tools 
https://scottlilly.com/testing-different-tools-techniques-and-practices-to-improve-c-programming-code-quality/
https://blog.ndepend.com/c-tools-help-code-quality/
https://ardalis.com/how-to-become-master-writing-c-code
https://www.viva64.com/en/b/0537/


*Retornar valores por defecto, para saber si no se metoò en algun condicional
*Manejo de excepciones
*DRY No repetir la lògica
*constantes estaticas
*Una sola responsabilidad en un mètodo, si tiene mas de una responsabilidad entonces al modificarlo podria afectar lo ademàs
*Pruebas unitarias
*Nombre de las variables
*Evitar nùmero màgicos con Enum
public enum AccountStatus
{
  NotRegistered = 1,
 SimpleCustomer = 2
}
Como si fuera un objeto
 AccountStatus accountStatus
// AccountStatus.SimpleCustomer
* Otra tecnica para números mágicos es const constantes
, en caso de que no deban elegir de una lista.

Se podría tener en una clase tambien
public static class Constants
{
  public const int MAXIMUM_DISCOUNT_FOR_LOYALTY = 5;


*No dejar lineas largas de calculos, mejor partirlo en 2 lineas
* EN un switch 
      default:
        throw new NotImplementedException();
* Métodos de extension. Clase publica static, metodo static en el primer parámetro colocar this.
