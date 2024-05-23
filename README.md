The **XAML file** has 3 elements:
- "mainLabel", representing a Label, and text set to "Hello World".
- "sizeSlider", representing a Slider, with Minimum and Maximum values set to 10 and 100 respectively. The default value is 10.
- "setSizeBtn", representing a Button.

**Your task** is to bind the button's `Clicked` event handler to an event handler method which sets the `FontSize` property of the **label** to the value of the **slider**. 

**You only have to modify the C# file.**

In summary, you will have to write the code for:
- A new method called `SetSize` and it should have the same signature as the EventHandler.
- The method should set the `FontSize` property equal to the `Value` property of the slider.
- Adding the `SetSize` method to the `Clicked` event handler of the button element.
