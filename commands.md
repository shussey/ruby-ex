oc logs -f bc/ruby-ex

    Application is not exposed. You can expose services to the outside world by executing one or more of the commands below:
oc expose svc/ruby-ex
    
Run 'oc status' to view your app

To Manual BUild after changeing code 
oc start-build ruby-ex