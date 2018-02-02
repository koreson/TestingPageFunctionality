# TestingPageFunctionality
Project - Dani's Barber Shop 
Testing each page functionality 


package Pagefunctionality;

import java.util.concurrent.TimeUnit;

import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class MenHairsStylingGrooming {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

        System.setProperty("webdriver.chrome.driver", "C:\\Users\\user\\Downloads\\chromedriver_win32\\chromedriver.exe");
        
        WebDriver driver = new ChromeDriver();
        
        driver.get("https://ueni.com/en-gb/business/london-w6/barber/danisbarbershop-hammersmith"); 
        
        driver.manage().timeouts().implicitlyWait(10, TimeUnit.SECONDS);
        
        // Men Hairs Styling Grooming has six pages, removed double slide ( // )to run the functionality of each page.  
        
        driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div:nth-child(1)")).click();
   
        //driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div:nth-child(2)")).click();
        
        //driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div:nth-child(3)")).click();
        
        //driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div:nth-child(4)")).click();
        
        //driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div:nth-child(5)")).click();
        
        //driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div:nth-child(6)")).click();
       
	 }

}

