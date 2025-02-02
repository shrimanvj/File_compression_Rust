# File Compression in Rust

A simple Rust program to compress files using the **flate2** crate.

## 🚀 Features
- Compresses files using **Gzip compression**  
- Displays source and compressed file sizes  
- Measures compression time  

## 🛠️ Installation & Usage
1. Clone the repository:  
   ```bash
   git clone https://github.com/shrimanvj/File_compression_Rust.git
   cd File_compression_Rust
Build the project:
cargo build

Run the compression command:
cargo run -- "source_file.pdf" compressed_file.gz

📦 Dependencies
flate2 (for Gzip compression)
