package royanmobiletesting;


import java.net.MalformedURLException;
import java.net.URISyntaxException;

import org.openqa.selenium.By;
import org.testng.Assert;
import org.testng.annotations.Test;
import io.appium.java_client.AppiumBy;


public class AppiumBasics extends BaseTest {
    
	@Test
	public void AppiumTest()  throws MalformedURLException, URISyntaxException{
		
		 // Actual Automation Code
		// Xpath, id, accessibilityId, classname, androidUIAutomator
		// used .AppiumBy for accessibilityId and androidUIAutomator
	    driver.findElement(AppiumBy.accessibilityId("Preference")).click();
		driver.findElement(By.xpath("(//android.widget.TextView[@resource-id='android:id/text1'])[3]")).click();
        driver.findElement(By.id("android:id/checkbox")).click();
        driver.findElement(By.xpath("(//android.widget.RelativeLayout)[2]")).click();
       String alertTitle =  driver.findElement(By.id("android:id/alertTitle")).getText();
       Assert.assertEquals(alertTitle, "WiFi settings");
	    driver.findElement(By.id("android:id/edit")).sendKeys("Arindam330");
	    driver.findElements(AppiumBy.className("android.widget.Button")).get(1).click();
	}

}
 