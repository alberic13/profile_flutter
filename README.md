# profile_flutter
simple profile make by flutter 

import 'package:flutter/material.dart';

class HomeScreen extends StatelessWidget {
  const HomeScreen({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor: const Color.fromARGB(255, 221, 161, 228),
      appBar: AppBar(
        backgroundColor: const Color.fromARGB(255, 158, 134, 244),
        title: Text("Biodata Mahasiswa"),
      ),
      body: Padding(
        padding: const EdgeInsets.all(16.0),
        child: Column(
          crossAxisAlignment: CrossAxisAlignment.start,
          children: [
            Row(
              children: [
                Icon(Icons.person, size: 40),
                SizedBox(width: 10),
                Text(
                  "Muchammad Zalde Zahwa Putra",
                  style: TextStyle(fontSize: 18, fontWeight: FontWeight.bold),
                ),
              ],
            ),
            SizedBox(height: 20),
            Text(
              "Nama: Muchammad Zalde Zahwa Putra",
              style: TextStyle(fontSize: 16),
            ),
            Text(
              "Kelas: SI 23A1",
              style: TextStyle(fontSize: 16),
            ),
            Text(
              "Tempat Tinggal: Sukoharjo",
              style: TextStyle(fontSize: 16),
            ),
            Text(
              "NIM: 230101021",
              style: TextStyle(fontSize: 16),
            ),
          ],
        ),
      ),
    );
  }
}
