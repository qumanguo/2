# 2
    public void test(){
        long start = System.currentTimeMillis();
        int a = 0;
        try {
            for (int i=0;i<1000000000;i++){
                a++;
            }
        }catch (Exception e){
            e.printStackTrace();
        }
        long useTime = System.currentTimeMillis()-start;
        System.out.println(useTime);
    }
