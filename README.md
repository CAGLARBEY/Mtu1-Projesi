# PLC Tabanlı Paketleme Sistemi | PLC-Based Packaging System

## 🏭 Proje Özeti | Project Overview
**Türkçe**:  
Bu proje, PLC kontrollü bir paketleme sisteminin simülasyonunu içerir. Factory I/O ile oluşturulan sanal ortamda çalışan sistem, kızılötesi sensörlerle ürün algılama ve paketleme işlemlerini otomatize eder. Endüstriyel otomasyon uygulamaları için geliştirilmiş PLC tabanlı paketleme sistemi. Kızılötesi sensörlerle ürün konum ve varlık kontrolü yaparak paketleme işlemini gerçekleştirir.

**English**:  
This project contains the simulation of a PLC-controlled packaging system. The system operating in a virtual environment created with Factory I/O automates product detection and packaging processes using infrared sensors. A PLC-based packaging system developed for industrial automation applications. It performs packaging operations using infrared sensors for product position and presence detection.

## 🛠️ Teknik Özellikler | Technical Specifications

### 🔌 Donanım | Hardware
**Türkçe**:  
- **PLC Modeli**: Siemens S7-1200 (Simülasyon)
- **Sensörler**: 
  - Kızılötesi Ürün Algılama Sensörü
  - Kızılötesi Konum Sensörü
- **Aktüatörler**: 
  - Konveyör Bant Motoru
  - Pnömatik Paketleme Ünitesi

**English**:  
- **PLC Model**: Siemens S7-1200 (Simulation)
- **Sensors**: 
  - Infrared Product Detection Sensor
  - Infrared Position Sensor
- **Actuators**: 
  - Conveyor Belt Motor
  - Pneumatic Packaging Unit

### 🖥️ Yazılım | Software
**Türkçe**:  
- **PLC Programlama**: TIA Portal (LAD/FBD)
- **Simülasyon**: Factory I/O
- **HMI**: WinCC Runtime (Basit Arayüz)

**English**:  
- **PLC Programming**: TIA Portal (LAD/FBD)
- **Simulation**: Factory I/O
- **HMI**: WinCC Runtime (Basic Interface)

## 📋 Sistem Çalışma Prensibi | System Operation

### 🔄 İş Akışı | Workflow
**Türkçe**:  
1. Ürün kızılötesi sensör ile algılanır
2. Konveyör bant ürünü paketleme alanına taşır
3. İkinci kızılötesi sensör ürün pozisyonunu doğrular
4. PLC pnömatik sistemi aktive ederek paketleme yapar
5. Paketlenmiş ürün çıkış konveyörüne yönlendirilir

**English**:  
1. Product is detected by infrared sensor
2. Conveyor belt transports product to packaging area
3. Second infrared sensor verifies product position
4. PLC activates pneumatic system to perform packaging
5. Packaged product is directed to output conveyor
