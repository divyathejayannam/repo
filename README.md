# thejarepo
java fundamentals 
if (tv1!= null)
        { 
          parameter1 = tv1.getColumnValue().toString();
          parameter2 = tv2.getColumnValue().toString();
  
  jcsOut.println("parameter1: " + parameter1);
  jcsOut.println("parameter1: " + parameter2);
  
          DateTimeZone now  = new DateTimeZone();
          long delta        = now.getUTCMilliSecs() - Long.parseLong(parameter1) * 1000;
