var interleave = require('interleave'),
    _ = require('underscore'),
    opts = {
        stylus: {
            plugins: {
                nib: require('nib')
            },
            
            urlEmbed: true
        }
    };

task('default', function() {
    interleave('src/css', _.extend({
        path: 'css'
    }, opts));
});