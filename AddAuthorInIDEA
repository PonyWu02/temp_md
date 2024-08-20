To change the date format in IntelliJ IDEA's file templates to `2024-08-19`, you can modify the template as follows:

### Step 1: Modify the Date Format in the File Template
1. **Open IntelliJ IDEA**.
2. **Go to Settings/Preferences**:
   - On Windows/Linux: `File` > `Settings`.
   - On macOS: `IntelliJ IDEA` > `Preferences`.

3. **Navigate to File and Code Templates**:
   - In the Settings/Preferences dialog, go to `Editor` > `File and Code Templates`.

4. **Select the Code Template to Modify**:
   - Select the template you want to modify, such as `Class` for Java classes.

5. **Modify the Template with the Desired Date Format**:
   - Replace the `${DATE}` variable with a Groovy script to format the date as `YYYY-MM-DD`. Here’s how you can do it:
   ```java
   /**
    * @author ${USER}
    * @date ${YEAR}-${MONTH}-${DAY}
    */
   public class ${NAME} {
       // Your code here
   }
   ```

   - `${YEAR}`: Inserts the current year.
   - `${MONTH}`: Inserts the current month in two digits.
   - `${DAY}`: Inserts the current day in two digits.

   By using dashes `-` between these variables, the date will be formatted as `2024-08-19`.

6. **Save Your Changes**:
   - Click `OK` or `Apply` to save your changes.

### Step 2: Test the Configuration
1. **Create a New Class**:
   - Right-click on your project’s source folder and select `New` > `Java Class`.

2. **Check the Generated File**:
   - The new class file should now include the date in the format `2024-08-19`.

### Example Result:
When you create a new Java class, it might look like this:

```java
/**
 * @author JohnDoe
 * @date 2024-08-19
 */
public class MyNewClass {
    // Your code here
}
```

This approach will ensure that the date is automatically formatted as `YYYY-MM-DD` whenever you create a new file using the template.
