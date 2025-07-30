"# fuku" 



npm install 20.19
npm use 20.19
node -v

--old
v16.13.1

git checkout -b upgrade/angular-12-to-13
git add .
git commit -m "chore: prepare for Angular 13 upgrade"

ng update @angular/cli@13 @angular/core@13

ng version
สรุปสถานะของ Angular CLI, Angular Framework, TypeScript, RxJS, Zone.js และ Node.js ในทีเดียว

npm list --depth=0
แสดงชื่อและเวอร์ชันของทุกแพ็กเกจภายใต้ dependencies/devDependencies โดยไม่แสดงไลบรารีย่อย

npm list <package>
ดูว่าโปรเจ็กต์ติดตั้ง <package> เวอร์ชันไหน (เช่น @angular/core)

npm outdated
เปรียบเทียบ “Current” (ที่ติดตั้ง), “Wanted” (ตาม semver ใน package.json) และ “Latest” (เวอร์ชันใหม่สุดบน npm registry) เพื่อวางแผนอัปเดตต่อไป

yarn list / yarn outdated
คำสั่ง tươngเทียมกันในกรณีใช้ Yarn แทน npm