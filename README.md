# QuestAPI_0225 - MEET10

Aplikasi Android Data Siswa berbasis Jetpack Compose, Retrofit 2, dan KotlinX Serialization.

## Fitur
- Menampilkan daftar siswa dari REST API (`bacaTeman.php`)
- Menambah data siswa baru (`insertTM.php`)
- Navigasi antar halaman menggunakan Navigation Compose
- Dependency Injection sederhana menggunakan `ContainerApp`

## Arsitektur
- **Model**: `DataSiswa`
- **Network**: Retrofit Service `ServiceApiSiswa`
- **Repository**: `RepositoryDataSiswa` & `JaringanRepositoryDataSiswa`
- **UI/ViewModel**: State-driven UI dengan `HomeViewModel` dan `EntryViewModel`
