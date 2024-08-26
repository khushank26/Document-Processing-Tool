### Document Processing Tool
## For problem statement:  [COL106_Assignment_6_v0.pdf](https://github.com/user-attachments/files/16754357/COL106_Assignment_6_v0.pdf)
## To run code:
  # Go to ***dict.cpp*** file --> Create a new Dict class and insert your document lines (Just copy paste those lines) and then use get_word_count method of Dict class.
## Example:

int main(){

     Dict book=Dict();
     book.insert_sentence(1,1,1,1,"but afterwards found a very valuable customer in the native of South Afric");
     book.insert_sentence(1,1,1,1,"hurting a customer's who nearly lost his eye.");
     book.insert_sentence(1,1,1,1,"hurting a customer who nearly lost his eye.");
     cout<<book.get_word_count("customer");

}

  
