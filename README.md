# Hospital-Management-System-Project
My project was created to make  Hospital Management System Project more easier and accurate
Description of my self-made Hospital Management System Project:

1.Introduction:
  This project is about a system to manage records of patients and condition of their health for proper medication and avoid any kind of time delay and clinical error. This project is a simple console-based application written in C, created to make management system in a hospital easier. It allows a user to admit new patient, discharge a patient through online platform, add a doctor or get appoinment and show the list of available doctors. This description provides a overview of the projects features, functionality and code structure.

2.Project Structure:
  This project consists of a C source file and a few add-in files. It has some standard libraries of various functionalities.

3.Key Components:
  The project compromises several key components:
    i.File Handling:
      It uses several files to store patient's identifier and data about condition of patient's body. Data of a patient and his admission process is stored in the file admit_patient.txt and data of available doctors is stored in doctor_list.txt . A user can admit his patient to the hospital with proper information and also can check the doctors list to see the available doctors and appoint a doctor for the patient who is suitable for him. 
    ii.Data Completion:
      Users can add or remove patients and doctors. They add all kind of information that is related to health like blood preasure, HDL, LDL and etc.
    iii.Records:
      It also records old patients even if he is deleted from the appoinment list, also store the detailes of the doctors who aren't available anymore.
  
  4.Functions:
    i.admitPatient
      This function is used to admit a patient or enter his info into the system.
    ii.showPatientList
      This function is used to see the list of admitted patients or entered info of patients into the system.
    iii.discgargePatient
      This function is used to discharge a previously admitted patient and erase some of his brief info from the system.
    iv.addDoctor
      This function is used to add a suitable and available doctor or appoint a doctor to the patient by merging their data into the system.
    v.showDoctorList
      This function is used to check the list of available doctors who are mentioned in the system.

  5.Mainmenu:
    Mainmenu has six options to simplify the outlook and make the system and process more user friendly. Those options are,
    i.Admit a Patient             : To admit a patient
    ii.Show admitted Patients List: To see the list of admitted patients
    iii.Discharge a Patient       : To discharge a patient
    iv.Add a Doctor               : To add or appoint a doctor to the list and patient
    v.Show Doctor List            : To see the list of available doctors
    vi.Exit                       : To leave the system

  6.Error handling:
    The project sometimes show some errors while inputing data. And we are working on it to solve the errors, soon it will become even more suitable for commercial use.
  
  7.Conclusion:
    We have tried our best to make a easier and more user friendly Hospital management system. It's not perfect but we are working to upgrade it to such mergin that it may become a highly recommended management system for world-class hospitals. Thanks for going through the whole description.
