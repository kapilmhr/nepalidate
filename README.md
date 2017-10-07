# nepalidate
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}


	dependencies {
	        compile 'com.github.kapilmhr:nepalidate:1.0.0'
	}

#Initialize
DateConverter dateconverter = new DateConverter();
dateconverter.getNepDate(year,month,day);
