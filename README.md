# CodingStandards
don't fuck up

##General
###functions
+ privateMethod();
+ PublicMethod();
+ internalMethod();

###variables
+ PublicVariable
+ privateVariable
+ \_internalVariable


###Don't
- Use_Snake_Case_Ever
- var myVariable = "you are a sick fuck. use your types!";

##Language Specific
###C-Sharp
- All brackets get their own line
- Don't not use inline if/else statements
- Use of var is restricted (temp variables are allowed, if casted in the same line)

```csharp
public void PublicMethod()  //capitalize public methods
{                           //brackets get their own line
  //do something
}
private void privateMethod() //lowwercase private methods
{
  //do something
}

public class SomeClass
{
  public string publicMember = "public";
  private string _instanceVariable = "underscore";
  
  public SomeClass()
  {
    //constructor comes after members
  }
  
  public string PublicVariable
  {
    get { return _instanceVariable; }
    set 
    {
      if(_instanceVaraible != value)
      { //always use brackets for if statements
        _instanceVaraible = value;
      }
    }
  }
  
  private void privateMethod()
  { 
    //do something
  }
  public void PublicMethod()
  {
    this.privateMethod(); //use the 'this' keyword, when calling methods an instance object
  }
}
```

###CSS
- Open bracket ends a previous line
- Close bracket has its own line

```css
.class { /* opening brackets end the selector line */
  color: #EEE; /* use short color codes */
  background-color: #333; /* only one attribute per line */
} /* close brackets get their own line */

.class a { /* add more specific selectors below */
  color: #FFF; 
}
```
###Javascript
Don't use Javascript




