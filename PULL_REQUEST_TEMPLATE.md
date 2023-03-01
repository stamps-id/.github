# Developer Checklist
Pastikan checklist dibawah sudah dikerjakan sebelum submit PR :

- [ ] Fix/Ref issue #... (buat issue dulu kalau belum ada)
- [ ] Coding sudah dibaca ulang
- [ ] Print statement sudah dihapus
- [ ] Code indentation dan syntactical issues sudah dicek (spacing yang sesuai di sekitar keywords, dll)
- [ ] Penamaan variable sudah dicek
- [ ] Fitur sudah ditest
- [ ] Screenshots sudah dilampirkan (bila ada)
- [ ] Update changelog.md (jika dibutuhkan)

# Reviewer Checklist
- [ ] Memastikan issue terkait dengan PR nya sudah dibuat
- [ ] Memastikan print/Log/pdb statement sudah di hapus
- [ ] Penamaan variable sudah make sense dan sesuai
- [ ] Changelog sudah di attach
- [ ] Sudah melampirkan test (Apabila perlu)

# Screenshot Mockup
| Dev| Mockup |
|:-------------------------:|:-------------------------:|
 Attach here | Attach here


# Issue Level Mobile
| Level | Description |
| --- | --- |
| Trivial | Ubah wording, fix tampilan minor, menampilkan data ke halaman yang sudah existing |
| Easy | Check library dengan ada perubahan code*, Ubah layout, ubah color scheme, fix minor bug terkait UI,  integrasi 3rd party (Analytics), Penambahan field baru di model existing |
| Medium | Check library dengan ada perubahan code*, penambahan fitur baru tanpa merubah flow, implementasi fitur baru*, integrasi 3rd party, Migrasi field dan penambahan model |
| Hard | Perubahan flow, implementasi fitur baru*, perubahan UI dengan nested recyclerView/TableView, performance issue, intergrasi native 3rd party |
| Very Hard | Performance issue dengan layout yang complex |

# Issue Level Backend
| Level | Description |
| --- | --- |
| Trivial | wording, bump library, menampilkan data ke halaman yang sudah existing |
| Easy | field baru/ubah field tanpa migrasi data, CRUD* |
| Medium | debugging*, import/export data, migrasi data, penambahan fitur baru tanpa ubah flow |
| Hard | debugging*, integrasi 3rd party, penambahan fitur baru dengan ubah flow*, refactoring code base, setup server |
| Very Hard | Penambahan fitur baru ubah flow* |
