# mvc-controller-view
Movie Controller ile aynı isimlerde view döndürüyoruz
<pre>
public class MovieController : Controller
    {
        public IActionResult Index()
        {
            return View();
        }

        public IActionResult Details()
        {
            return View();
        }

        public IActionResult List()
        {
            return View();
        }
    }
</pre>
Views Klasörümüzün içinde ki Movie klasörünün içinde ise ".cshtml" dosyalarımızı ekliyoruz.

![](https://i.resim.host/xaRyJC.png)

Ve çalıştırdığımızda ise sayfalarımızın çalıştığını görebiliyoruz.

![](https://i.resim.host/folhkY.png)
