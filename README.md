# Buttons
CopyPasta for different button types

```java
toggleButton.setOnClickListener(new View.OnClickListener() {
  public void onClick(View view) {
      // am I checked?
      boolean on = ((ToggleButton) view).isChecked();
      
      if (on) {
          // write something to do if checked below
          
      } else {
          // write something to do if not checked below
          
      }
  }
}
```
