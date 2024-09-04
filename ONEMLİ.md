<!--
dataSource: Grid'in veri kaynağını tanımlar. Örnekte, grid'e yüklemek için statik bir veri kümesi oluşturdum.
schema: Veri kaynağının yapısını tanımlar ve Grid'in bu veriyi nasıl işleyeceğini belirtir.
columns: Grid'in sütunlarını tanımlar. Her sütun, bir veri alanını (field) ve başlığını (title) belirtir.
sortable: Kullanıcıların sütun başlıklarına tıklayarak grid verilerini sıralamasına izin verir.
pageable: Sayfalandırmayı etkinleştirir. Bu özellik, büyük veri setlerini yönetmek için kullanışlıdır.
height: Grid'in yüksekliğini belirler.

pageable: Sayfalandırma özelliğini etkinleştirir. Kullanıcıların verileri sayfa sayfa görüntülemesini sağlar. Örneğin: pageable: true
sortable: Sütun başlıklarına tıklayarak verileri sıralamayı etkinleştirir. Örneğin: sortable: true
filterable: Filtreleme özelliğini etkinleştirir. Kullanıcıların griddeki verileri filtrelemelerine olanak tanır. Örneğin:filterable: true
groupable: Sütunlar üzerinden gruplandırmayı etkinleştirir. Kullanıcıların verileri belirli sütunlara göre gruplandırmasını sağlar. Örneğin:groupable: true
selectable: Seçilebilir satırları veya hücreleri belirtir. Tek veya çoklu seçim modlarını destekler. Örneğin: selectable: "multiple"
editable: Grid'in düzenleme modunu ayarlar. Satır veya hücre bazında düzenleme yapmayı sağlar. Örneğin: editable: "inline"
resizable: Sütunların yeniden boyutlandırılmasına izin verir. Kullanıcılar sütun genişliklerini sürükleyerek ayarlayabilirler. Örneğin:resizable: true
reorderable: Sütunların yerlerinin değiştirilmesine izin verir. Kullanıcılar sütun başlıklarını sürükleyerek sıralarını değiştirebilirler.Örneğin:reorderable: true

scrollable: Grid'in kaydırma davranışını ayarlar. Hem dikey hem de yatay kaydırma yapılabilir. Örneğin:scrollable: true
navigatable: Klavye ile grid içinde gezinmeye olanak tanır. Kullanıcılar, ok tuşları ve diğer klavye kısayollarıyla grid içinde hareket edebilir. Örneğin:navigatable: true
dataSource: Grid'in veri kaynağını tanımlar. Statik veya dinamik verilerle kullanılabilir ve AJAX isteklerini destekler.

columns: Grid sütunlarını yapılandırır. Her sütun için alan, başlık, genişlik, şablon gibi özellikler belirlenebilir.
columns: [
    { field: "name", title: "İsim", width: "100px" },
    { field: "age", title: "Yaş", width: "50px" }
]

toolbar: Grid'in üstünde bir araç çubuğu ekler. Kullanıcılar veri ekleme, silme veya özelleştirilmiş işlemler yapabilirler.
toolbar: ["create", "save", "cancel"]

detailTemplate: Satır detay görünümünü tanımlar. Grid satırlarının altına açılabilir bir detay paneli ekler.
detailTemplate: "<div>Detay Bilgisi: #: data.detailInfo #</div>"

noRecords: Veri olmadığında görüntülenecek mesajı veya şablonu tanımlar.
noRecords: {
    template: "Veri bulunamadı."
}

height: Grid'in yüksekliğini belirler. Sabit bir değer veya yüzde cinsinden bir değer alabilir.
columnMenu: Sütun menüsünü etkinleştirir. Kullanıcılar sütunları gizleyebilir, gösterebilir veya sıralama ve filtreleme yapabilir.columnMenu: true
columnVirtualization: Büyük veri setlerinde performansı artırmak için sütun sanallaştırmayı etkinleştirir.columnVirtualization: true
rowTemplate: Her bir satırın görünümünü özelleştirmek için şablon kullanır.
rowTemplate: "<tr><td>#: name #</td><td>#: age #</td></tr>"

excel: Grid'deki verilerin Excel formatında dışa aktarılmasını sağlar.
excel: {
    fileName: "GridVerisi.xlsx",
    filterable: true
}

pdf: Grid'deki verilerin PDF formatında dışa aktarılmasını sağlar.
pdf: {
    fileName: "GridVerisi.pdf",
    allPages: true


--GRİD YAPISI

VERİ EKLEME

}
