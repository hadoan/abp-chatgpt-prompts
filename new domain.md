## HTML
here is the sample for title property of domain Patient  
    <div class="mt-2">
        <label for="patient-title">Title</label><span> * </span>
        <input type="text" id="patient-title" class="form-control" formControlName="title" />
    </div>

generate for all properties Propert1, Property2,...
Just write the code



## Build form

 buildForm() {
    this.form = this.fb.group({
      name: [this.selectedPatient.firstName || '', Validators.required],
      // Include other properties as needed
    });
  }

add properties lastName
