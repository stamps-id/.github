# Developer Checklist
Pastikan checklist dibawah sudah dikerjakan sebelum submit PR :

- [ ] Fix/Ref issue #... (buat issue dulu kalau belum ada)
- [ ] Coding sudah dibaca ulang
- [ ] Print/Log/debugging statements sudah dihapus
- [ ] Code indentation dan syntactical issues sudah dicek (spacing yang sesuai di sekitar keywords, dll)
- [ ] Penamaan variable sudah make sense dan sesuai
- [ ] Fitur sudah ditest dari browser/simulator/device
- [ ] Screenshots sudah dilampirkan (bila ada)
- [ ] Update changelog.md (jika dibutuhkan)
- [ ] Sudah melampirkan test (Apabila perlu)
- [ ] Code security sudah di check

# Reviewer Checklist
- [ ] Difficulty level sudah di-label
- [ ] Pastikan issue terkait sudah dibuat
- [ ] Pastikan Print/Log/debugging statements sudah di hapus
- [ ] Penamaan variable sudah make sense dan sesuai
- [ ] Changelog sudah di attach
- [ ] Test sudah dilampirkan
- [ ] Screenshot sudah dicek
- [ ] Pastikan code secara securitu sudah di check

# Screenshot Mockup
| Dev| Mockup |
|:-------------------------:|:-------------------------:|
 ![image](https://user-images.githubusercontent.com/21882504/224208793-9898699c-9d25-4a9e-b6ac-c3687daab60d.png) | ![image](https://user-images.githubusercontent.com/21882504/224208801-887df596-4964-4499-b109-adf4ccbae706.png)


# Issue Level Mobile
| Level | Description |
| --- | --- |
| Trivial | Ubah wording, fix tampilan minor, menampilkan data ke halaman yang sudah existing |
| Easy | Upgrade third party library*, ubah layout, fix minor bug terkait UI, integrasi 3rd party SDK*, penambahan field baru di model existing |
| Medium | Upgrade third party library*, penambahan fitur baru, integrasi 3rd party SDK*, migrasi field dan penambahan model |
| Hard | Perubahan user journey, implementasi fitur baru yang complex, development UI dengan nested recyclerView/TableView, performance improvements, intergrasi native 3rd party |
| Very Hard | Performance issue dengan layout yang complex |

# Issue Level Backend
| Level | Description |
| --- | --- |
| Trivial | wording, upgrade library, menampilkan data ke halaman yang sudah existing |
| Easy | field baru/ubah field tanpa migrasi data, CRUD*, bug fixing |
| Medium | bug fixing*, import/export data, migrasi data, penambahan fitur baru*, refactoring code base*, performance improvements* |
| Hard | bug fixing*, integrasi 3rd party, penambahan fitur baru*, refactoring code base*, setup server, improvements* |
| Very Hard | Penambahan fitur baru ubah flow*, penambahan fitur baru* |

* Tingkat kesulitan beragam, tergantung issue
