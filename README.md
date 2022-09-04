[Patika.dev](https://github.com/mordulu)


Dosyalarımın içinde yer alan program.cs'ye girilme zahmeti olmaması adına aşağıya çalışmamı önizleme olarak ekliyorum(süslü parantezler önizlemede hata verdiğinden konumlandırmalarına dikkat etmeyiniz)

# Array Sınıfları Çalışması

    // See https://aka.ms/new-console-template for more information

    //Sort
    int[] sayiDizisi = {23,12,4,86,72,3,11,17};

    System.Console.WriteLine("***** Sırasız Dizi *****");
    foreach (var sayi in sayiDizisi)
    System.Console.WriteLine(sayi);
    
    System.Console.WriteLine("***** Sırasız Dizi *****");
    Array.Sort(sayiDizisi);

    foreach (var sayi in sayiDizisi)
    System.Console.WriteLine(sayi);

    //Clear
    System.Console.WriteLine("***** Array Clear *****");
    //sayiDizisi elemanlarını kullanarak 2.index ten itibaren 2 tane elemanı 0'lar.
    Array.Clear(sayiDizisi,2,2);
    foreach (var sayi in sayiDizisi)
    System.Console.WriteLine(sayi);

    //Reverse
    System.Console.WriteLine("***** Array Reverse *****");
    Array.Reverse(sayiDizisi);
    
    foreach (var sayi in sayiDizisi)
    System.Console.WriteLine(sayi);

    //Indexof
    System.Console.WriteLine("***** Array IndexOf *****");

    System.Console.WriteLine( Array.IndexOf(sayiDizisi,23));

    //Resize
    Console.WriteLine(" ***** Array Resize *****");
    Array.Resize<int>(ref sayiDizisi,9);
    sayiDizisi[8] = 99;

    foreach (var sayi in sayiDizisi)
    System.Console.WriteLine(sayi);

 
