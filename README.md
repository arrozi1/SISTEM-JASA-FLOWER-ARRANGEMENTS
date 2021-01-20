@ Class Diagram
FlowerArrangements <|-- Customer
    
    class FlowerArrangements {
      +Int No_Nota
      +Int Tanggal_Pemesanan
      +Int Tanggal_Pengantaran      
    }
    
    class Customer{
      +Int No_Nota
      +Varchar Nama
      +Varchar Alamat
    }
