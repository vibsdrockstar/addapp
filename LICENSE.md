#summmation mobile application
public void addListenerOnButton(){
edittext1=(Edit Text)findViewById(R.id.editText1); 
edittext2=(Edit Text)findViewById(R.id.editText2);
buttonSum=(Button)findViewById(R.id.button1);
buttonSum.setOnClickListener(new OnClickListener(){  
  
            @Override  
            public void onClick(View view) {  
                String value1=edittext1.getText().toString();  
                String value2=edittext2.getText().toString();  
                int a=Integer.parseInt(value1);  
                int b=Integer.parseInt(value2);  
                int sum=a+b;  
    Toast.makeText(getApplicationContext(),String.valueOf(sum),Toast.LENGTH_LONG).show();  
            }  
              
        });  
