Notes
=====

				 this->Hide();
				 Application::Exit();

Private Notes Do Not Edit OK!


			
			// This will check text box!
			 if (textBox3->Text == "QuantumWorks")
			 {
				 MyForm1^ myForm1 = gcnew MyForm1();
				 myForm1->Show();
			 }
			 
			 
			 
			 
			 
			 
			 
			 
			 
			 
			 
			 //main stuff to create windows form!
			 
			 #include "MyForm.h"

using namespace System;
using namespace System::Windows::Forms;

[STAThread]
void main(array<String^>^ arg) {
	Application::EnableVisualStyles();
	Application::SetCompatibleTextRenderingDefault(false);

	TestForms::MyForm form;
	Application::Run(%form);
}  
