# Lab-8_202001464
# Software Engineering IT314

Name : Smit P. Bhavsar

Student Id : 202001464

## Lab 8 Unit Testing with JUnit

**Code:**

![image](https://user-images.githubusercontent.com/107932317/233594515-5bd00cd7-2cce-40e3-8d8f-299926771bba.png)

**Lab Exercise:**

**1. Create a new Eclipse project, and within the project create a package.**

![image](https://user-images.githubusercontent.com/107932317/233594626-61dfb5cc-9f6e-4b59-a138-cd81b790b419.png)

![image](https://user-images.githubusercontent.com/107932317/233594686-f5b79d69-1373-420c-b394-72b0ea4a776d.png)

**2. Create a class for a Boa.**

![image](https://user-images.githubusercontent.com/107932317/233594784-ad216efd-a9ea-432a-9c5e-56d9985ab8c5.png)

**3. Follow the instructions in the JUnit tutorial in the section “Creating a JUnit Test Case in Eclipse”. You’ll be creating a test case for the class Boa. When you’re asked to select test method stubs, select both isHealthy() and fitsInCage(int).**

**Test Case Code:**

![image](https://user-images.githubusercontent.com/107932317/233594915-bcb47bcc-1a0e-4d9a-affd-ac4b0fd25450.png)

**4. Now it’s time to write some unit tests. Notice that the BoaTest class that JUnit created for you contains stubs for several methods. The first stub (for the method setUp()) is annotated with @Before. The @Before annotation denotes that the method setUp() will be run prior to the execution of each test method. setUp() is typically used to initialize data needed by each test. Modify the setUp() method so that it creates a couple of Boa objects, as follows:**


![https://user-images.githubusercontent.com/107679126/233315241-5ead53ae-259f-4ec5-b116-7f4e4e13e831.png](https://user-images.githubusercontent.com/107679126/233315241-5ead53ae-259f-4ec5-b116-7f4e4e13e831.png)

**Test Case Code:**

![image](https://user-images.githubusercontent.com/107932317/233595165-b8e50579-bdbc-4a87-b3d0-4b2f5bab975c.png)

**5. JUnit also provided stubs for two test methods, each annotated with @Test. Work on the testIsHealthy() method first. The purpose of this method is to check that the isHealthy() method in the Boa class behaves the way it’s supposed to. In the JUnit tutorial, read the section on “Writing Tests”. Modify the testIsHealthy() method so that it checks the results of activating the isHealthy() method on the two Boa objects you created in setup(). Likewise, modify the testFitsInCage() method to test the results of that method. Make sure your test is robust; it should check the results when the cage length is less than the length of the boa, when the cage length is equal to the length of the boa, and when the cage length is greater than the length of the boa. Should you write tests for both jen and ken?Ans:** Yes, We should write tests for both Ken and Jen.

**6. Now you can run your tests. Read the section “Running Your Test Case” in the tutorial. Did you get a green bar in the JUnit pane? If you got a red bar, use the output in the JUnit pane to determine which test(s) failed. Fix your tests, and try running the test case again. It’s important to note that a red bar doesn’t necessarily mean that the test case is written incorrectly; it could be that the method that’s being tested isn’t correct. In fact, that’s what unit testing is supposed to do – help us find errors in our code. When a test fails, you need to determine if the error is in the test case itself or in the code it’s testing.**

**Test Case Code:**

![image](https://user-images.githubusercontent.com/107932317/233595507-93e7b33c-7a39-43a7-980c-18ece1152eaf.png)

**7. Add a new method to the Boa class, with this purpose and signature: // produces the length of the Boa in inches public int lengthInInches(){ // you need to write the body of this method } Add a new test case to the BoaTest class that tests the lengthInInches() method. Make sure you annotate the new test method with @Test. Run your tests.**

**Function added in the Boa Class:**

![https://user-images.githubusercontent.com/107679126/233316672-c31c46ac-4c27-4c12-ac06-36b9913e239e.png](https://user-images.githubusercontent.com/107679126/233316672-c31c46ac-4c27-4c12-ac06-36b9913e239e.png)

**Test Case Code:**

![https://user-images.githubusercontent.com/107679126/233317041-42579e88-0655-480e-95af-6375d0cd90c1.png](https://user-images.githubusercontent.com/107679126/233317041-42579e88-0655-480e-95af-6375d0cd90c1.png)
