# ConvertCultrue
Convert Culture App Wpf to Persian (RTL)

----------------------------------
Set Settings to Start App WPF
  
PersianCulture culture = new PersianCulture();

System.Threading.Thread.CurrentThread.CurrentCulture = culture;

System.Threading.Thread.CurrentThread.CurrentUICulture = culture;
