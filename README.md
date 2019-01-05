# Mengetahui-Suatu-Kuadran-Koordinat
    #include<iostream>
    #include<conio.h>
    using namespace std;

    int main()
    {
        int x,y;
        cout<<"================================="<<endl;
        cout<<"=MENCARI KUADRAN SUATU KOORDINAT="<<endl;
        cout<<"================================="<<endl;
        cout<<"masukan koordinat x\n";
        cin>>x;
        cout<<"masukan koordinat y\n";
        cin>>y;
        {
            if(x>=0 && y>=0)
                cout<<"berada dikuadran I "<<endl;
            if(x<=0 && y>=0)
                cout<<"berada dikuadran II "<<endl;
            if(x<=0 && y<=0)
                cout<<"berada dikuadran III "<<endl;
            if(x>=0 && y<=0)
                cout<<"berada dikuadran IV "<<endl;
        }
        return 0;
    }
   # Hasil
   ![img](https://raw.githubusercontent.com/AminPriadi/Mengetahui-Suatu-Kuadran-Koordinat/master/kuadran.png)
