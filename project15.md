# Documentation of project 15

1. I created a VPC and named it "VPC-ACS"

  ![Project14](images/image1.PNG)

2. I enabled the DNS hostnames

  ![Project14](images/image2.PNG)

3. I created an internet gateway and attched it to my vpc

    ![Project14](images/image3.PNG)
     ![Project14](images/image4.PNG)

4.  I created subnets

     ![Project14](images/image5.PNG)

5. I created Route tables and associated it with my subnets

       ![Project14](images/image6.PNG)
        ![Project14](images/image7.PNG)

6. I created six security groups

     ![Project14](images/image8.PNG)
      ![Project14](images/image9.PNG)
       ![Project14](images/image10.PNG)
        ![Project14](images/image11.PNG)
         ![Project14](images/image12.PNG)
          ![Project14](images/image13.PNG)
           ![Project14](images/image14.PNG)

7. I created two access points for wordpress and tooling

       ![Project14](images/image15.PNG)
        ![Project14](images/image16.PNG)
         ![Project14](images/image17.PNG)

8. I created a key and named it "ACS-rds"

     ![Project14](images/image18.PNG)

9. I created a subnet group

     ![Project14](images/image19.PNG)

10. I created a database
     
      ![Project14](images/image20.PNG)

11. I launched three new instances namely; bastion,nginx and webserver

     ![Project14](images/image21.PNG)

12. I installed the dependencies needed for the instances I created

     ![Project14](images/image22.PNG)
      ![Project14](images/image23.PNG)
       ![Project14](images/image24.PNG)
        ![Project14](images/image25.PNG)
         ![Project14](images/image26.PNG)
          ![Project14](images/image27.PNG)

13. I created target groups

      ![Project14](images/image28.PNG)
       ![Project14](images/image29.PNG)
        ![Project14](images/image30.PNG)
         ![Project14](images/image31.PNG)

14. I created AMI's
    
     ![Project14](images/image32.PNG)

15.  I created two load balancers; internal and external

    ![Project14](images/image33.PNG)
    ![Project14](images/image34.PNG)
    ![Project14](images/image35.PNG)

16. I created four launch templates

   ![Project14](images/image36.PNG)
   ![Project14](images/image37.PNG)
   ![Project14](images/image38.PNG)

17. I configured auto-scaling groups

   ![Project14](images/image39.PNG)
   ![Project14](images/image40.PNG)
   ![Project14](images/image41.PNG)
   ![Project14](images/image42.PNG)
   ![Project14](images/image43.PNG)
   ![Project14](images/image44.PNG)
   ![Project14](images/image45.PNG)
   ![Project14](images/image48.PNG)

18. I confirmed if my mysql was working fine
   
     ![Project14](images/image46.PNG)
     ![Project14](images/image47.PNG)

19. I created new records in my route53 hosted zones

     ![Project14](images/image49.PNG)
     ![Project14](images/image50.PNG)
     ![Project14](images/image51.PNG)

20. I confirmed if my target group was healthy

    ![Project14](images/image52.PNG)

21. I ssh into my instance to confirm if my commands ran very well without issues

    ![Project14](images/image53.PNG)
    ![Project14](images/image54.PNG)
    ![Project14](images/image55.PNG)
    ![Project14](images/image56.PNG)
    ![Project14](images/image57.PNG)
