# Not-Ortalama-Hesaplama

int matematik, fizik, kimya, biyoloji, tarih;

Scanner scanner = new Scanner(System.in);

System.out.println("Matematik Notunuz: ");
matematik = scanner.nextInt();

System.out.println("Fizik Notunuz: ");
fizik = scanner.nextInt();

System.out.println("Kimya Notunuz: ");
kimya = scanner.nextInt();

System.out.println("Biyoloji Notunuz: ");
biyoloji = scanner.nextInt();

System.out.println("Tarih Notunuz: ");
tarih = scanner.nextInt();

int toplamNot = matematik + fizik + kimya + biyoloji + tarih;
float ortalama = toplamNot / 5;

System.out.println(ortalama);
