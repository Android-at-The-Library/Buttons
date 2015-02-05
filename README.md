# Buttons
CopyPasta for different button types

```java
toggleButton.setOnClickListener(new View.OnClickListener() {
  public void onClick(View view) {
      // save whether 
      boolean on = ((ToggleButton) view).isChecked();
      
      if (on) {
          // something to do
      } else {
          // some other thing to do
      }
  }
}
```
