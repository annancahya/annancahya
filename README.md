#include <iostream>

using namespace std;

int main()
{
    
    int jumlah, pilihan, dibayar, harga, total;
    int beliLagi = 1;
    
    while(beliLagi == 1){
        cout << "Selamat Datang di KAK GARDEN :)"    <<endl;
        cout << "============================"       <<endl;
        cout << "Minuman yang tersedia :"            <<endl;
        
        cout << "1.Aqua                 = Rp.4000 "  <<endl;
        cout << "2.Sprite               = Rp.8000 "  <<endl;
        cout << "3.Menantea (Diskon 10%)= Rp.10000 " <<endl;
        cout << "4.Latte                = Rp.25000 " <<endl;
        cout << "5.Latuan (Diskon 25%)  = Rp.50000 " <<endl;
        cout << "==========================="        <<endl;
        cout << "Tidak jadi membeli? tekan (6)"      <<endl;
        cout << endl;
        cout << "MASUKKAN PILIHAN ANDA :";
        
        cin>>pilihan;
        switch (pilihan){

        case 1 :
            cout<<"Aqua"<<endl;
            harga=4000;
            cout<<"Masukkan Jumlah =";
            
            cin>>jumlah;
            cout<<endl;
            
            total = jumlah*harga;
            cout<<"Total harga yaitu ="<<total<<endl;
            cout<<"DIBAYAR =";
            
            cin>>dibayar;
            cout<<endl;
            
            cout<<"Kembalian yang diterima.. = "<<dibayar-total<<endl;

            cout << endl << "Apakah Anda ingin membeli minuman lain? (1 = ya, 2 = tidak) " << endl;
            cin >> beliLagi;
            break;
            
        case 2 :
            cout<<"Sprite"<<endl;
            harga=8000;
            cout<<"Masukkan Jumlah =";
            
            cin>>jumlah;
            cout<<endl;
            total = jumlah*harga;
            cout<<"Total harga yaitu ="<<total<<endl;
            cout<<"DIBAYAR =";
            
            cin>>dibayar;
            cout<<endl;
            
            cout<<"Kembalian yang diterima.. ="<<dibayar-total<<endl;

            cout << endl << "Apakah Anda ingin membeli minuman lain? (1 = ya, 2 = tidak) " << endl;
            cin >> beliLagi;
            break;
            
        case 3 :
            cout<<"Menantea"<<endl;
            harga=10000-(10000*10/100);
            cout<<"Masukkan Jumlah =";
            
            cin>>jumlah;
            cout<<endl;
            
            total = jumlah*harga;
            cout<<"Total harga yaitu ="<<total<<endl;
            cout<<"DIBAYAR =";
            
            cin>>dibayar;
            cout<<endl;
            
            cout<<"Kembalian yang diterima.. ="<<dibayar-total<<endl;

            cout << endl << "Apakah Anda ingin membeli minuman lain? (1 = ya, 2 = tidak) " << endl;
            cin >> beliLagi;
            break;
            
        case 4 :
            cout<<"Latte"<<endl;
            harga=25000;
            cout<<"Masukkan Jumlah =";
            
            cin>>jumlah;
            cout<<endl;
            
            total = jumlah*harga;
            cout<<"Total harga yaitu ="<<total<<endl;
            cout<<"DIBAYAR =";
            
            cin>>dibayar;
            cout<<endl;
            
            cout<<"Kembalian yang diterima.. ="<<dibayar-total<<endl;

            cout << endl << "Apakah Anda ingin membeli minuman lain? (1 = ya, 2 = tidak) " << endl;
            cin >> beliLagi;
            break;
            
        case 5 :
            cout<<"Latuan"<<endl;
            harga=50000-(50000*25/100);
            cout<<"Masukkan Jumlah =";
            
            cin>>jumlah;
            cout<<endl;
            
            total = jumlah*harga;
            cout<<"Total harga yaitu ="<<total<<endl;
            cout<<"DIBAYAR =";
            
            cin>>dibayar;
            cout<<endl;
            
            cout<<"Kembalian yang diterima.. ="<<dibayar-total<<endl;

            cout << endl << "Apakah Anda ingin membeli minuman lain? (1 = ya, 2 = tidak) " << endl;
            cin >> beliLagi;
            break;
            
            case 6 :
            cout<<"=================================" <<endl;
            cout<<"Semoga lain kali jadi beli ya kak" <<endl;
        
            }

        cout<<"================================="<<endl;
        cout<<"Terima Kasih Atas Kunjungan Anda "<<endl;
        cout<<"KAK GARDEN selalu memberikan yang Terbaik"<<endl;

    }

return 0;
}


https://www.loom.com/share/71c63b7c817c4061b0f8889c7379a41c
