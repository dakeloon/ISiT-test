# ISiT-test 
#include <iostream>
#include <cmath>

using namespace std;

int main() {
  float v = 0.009, d = 19.1, o = 1;
  float R, y;
  
  v = v * 0.0001;
  d = d / 1000;
  while (o <= 2) {
    R = o * d / v;
    if (R > 9.2 * pow(10, 5)) {
      y = 0.021 / pow(d, 3); 
    }
    else {
      y = pow(1.5 * pow(10, -6) / d + 1 / R, 0.3);
    }
    cout << "R=" << R << "\ty=" << y << endl; 
      
  o += 1;
  }
}
  while (o <= 10) {
    o = 5
    R = o * d / v;
    if (R > 9.2 * pow(10, 5)) {
      y = 0.021 / pow(d, 3); 
    }
    else {
      y = pow(1.5 * pow(10, -6) / d + 1 / R, 0.3);
    }
    cout << "R=" << R << "\ty=" << y << endl; 
      
  o += 5;
  }
  while (o <= 50) {
    o = 20
    R = o * d / v;
    if (R > 9.2 * pow(10, 5)) {
      y = 0.021 / pow(d, 3); 
    }
    else {
      y = pow(1.5 * pow(10, -6) / d + 1 / R, 0.3);
    }
    cout << "R=" << R << "\ty=" << y << endl; 
      
  o += 30;
  }
  if (o==100) {
    R = o * d / v;
    if (R > 9.2 * pow(10, 5)) {
      y = 0.021 / pow(d, 3); 
    }
    else {
      y = pow(1.5 * pow(10, -6) / d + 1 / R, 0.3);
    }
    cout << "R=" << R << "\ty=" << y << endl;
  }
  
} 
