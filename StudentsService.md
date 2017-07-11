
# Example Student Service


```C#
using System.Web.Http;
using StudentsDataAccess;

namespace StudentsService.Controllers
{
    public class StudentController : ApiController
    {
        public IEnumerable<Student> Get()
        {
            using (BetSatSargsyanEntities entities = new BetSatSargsyanEntities())
            {
                return entities.Students.ToList();
            }
             
        }

               public Student Get(int id)
        {
            using (BetSatSargsyanEntities entities = new BetSatSargsyanEntities())
            {
                return entities.Students.FirstOrDefault(e=>e.StudentID==id);
            }
        }
    }
}
```
