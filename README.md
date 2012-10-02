My first open-sources project. You don't need to do anything. Just create instance of UIView or UIViewController and put it in to the SmartAlerView.

The interface of the SmartAlerView speaks for itself:

	+(void)showTable:(NSString*)title 
		   withItems:(NSArray*)items
		  withTarget:(id)target 
		   andAction:(SEL)action;
	
	+(void)showTextField:(NSString*)title 
				withText:(NSString*)text 
			  withTarget:(id)target
			   andAction:(SEL)action;
	
	+(void)showColorDialogWithTarget:(id)target 
						   andAction:(SEL)action;

	- (id)initWithView:(UIView*)view 
			  andTitle:(NSString*)title 
			withTarget:(id)target 
			 andAction:(SEL)action;
	
	- (id)initWithController:(UIViewController*)controller 
					andTitle:(NSString*)title
				  withTarget:(id)target 
				   andAction:(SEL)action;



![](http://imglink.ru/pictures/08-11-09/e71decd35d6e315e355692a934ad0649.png)
![](http://imglink.ru/pictures/08-11-09/0c62ad312dfc5b3f876b9c5b36b9864b.png)
![](http://imglink.ru/pictures/08-11-09/a6ddde458ff707942bd05383305a0091.png)