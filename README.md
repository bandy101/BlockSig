# BlockSig
查看未知block类型的参数，主要用于越狱开发
- (BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions 
{
    // Override point for customization after application launch.
    
    [self test:^(UIImage *a){}];
  

    
    return YES;
}

-(void)test:(id)arg
{

    NSLog(@"signature %s", BlockSig(arg));
    
}
