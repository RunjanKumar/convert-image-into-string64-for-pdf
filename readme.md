 const imagePath = path.resolve(`${__dirname}../../../../public/images/mini-hearts-logo-no-background.png`);

        const imageBuffer = fs.readFileSync(imagePath);
        const base64Image = Buffer.from(imageBuffer).toString('base64');
        const srcAttribute = `data:image/png;base64,${base64Image}`;
